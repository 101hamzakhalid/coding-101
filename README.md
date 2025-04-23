
// Import SwiftUI framework
import SwiftUI

// Main app structure
@main
struct SimpleApp: App {
    var body: some Scene {
        WindowGroup {
            ContentView()
        }
    }
}

// Main view structure
struct ContentView: View {
    // State variables to store user input and greeting
    @State private var name: String = ""
    @State private var greeting: String = ""
    
    var body: some View {
        // Vertical stack for layout
        VStack(spacing: 20) {
            // App title
            Text("Welcome to Simple App")
                .font(.largeTitle)
                .fontWeight(.bold)
            
            // Text field for user input
            TextField("Enter your name", text: $name)
                .padding()
                .background(Color.gray.opacity(0.1))
                .cornerRadius(10)
                .padding(.horizontal)
            
            // Button to trigger greeting
            Button(action: {
                // Update greeting when button is pressed
                greeting = name.isEmpty ? "Please enter a name" : "Hello, \(name)!"
            }) {
                Text("Say Hello")
                    .font(.headline)
                    .foregroundColor(.white)
                    .padding()
                    .frame(maxWidth: .infinity)
                    .background(Color.blue)
                    .cornerRadius(10)
                    .padding(.horizontal)
            }
            
            // Display greeting message
            Text(greeting)
                .font(.title2)
                .foregroundColor(.secondary)
                .padding()
            
            // Spacer to push content up
            Spacer()
        }
        .padding(.top)
    }
}

// Preview provider for SwiftUI canvas
struct ContentView_Previews: PreviewProvider {
    static var previews: some View {
        ContentView()
    }
}
