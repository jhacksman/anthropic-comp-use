# Anthropic Computer Use API Demo for macOS (M2 MacBook)

This project demonstrates the implementation of Anthropic's new computer use functionality API on macOS, specifically optimized for M2 MacBooks. Our primary goals are to create a functional demo showcasing the API's capabilities in interacting with macOS desktop environments, optimize performance for M2 chip architecture, and provide a comprehensive guide for developers. We aim to have a working prototype ready within a week, with continuous improvements thereafter. Please note that this project is currently in active development and may undergo frequent updates.

## Project Overview

The Anthropic Computer Use API allows AI models to interact with computer desktop environments. This implementation focuses on macOS compatibility, particularly for M2 MacBook systems, leveraging the advanced capabilities of the M2 chip architecture.

## Features

- Seamless integration with Anthropic's Computer Use API
- Optimized performance for macOS on M2 MacBooks
- Example implementations of key API functionalities:
  - Screen capture and analysis
  - Keyboard and mouse input simulation
  - File system interactions
  - Application launching and control
- Interactive web interface for real-time API interaction
- Dockerized environment for easy setup and deployment

## How to Create and Set Up the Project on M2 MacBook

1. Ensure you have Xcode and Homebrew installed on your M2 MacBook.

2. Install Python 3.9 or later using Homebrew:
   ```
   brew install python@3.9
   ```

3. Clone the repository:
   ```
   git clone https://github.com/jhacksman/anthropic-comp-use.git
   cd anthropic-comp-use
   ```

4. Create and activate a virtual environment:
   ```
   python3 -m venv venv
   source venv/bin/activate
   ```

5. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

6. Set up environment variables:
   Create a `.env` file in the project root and add your Anthropic API key:
   ```
   ANTHROPIC_API_KEY=your_api_key_here
   ```

7. Run the application:
   ```
   python main.py
   ```

8. Access the web interface at `http://localhost:8080`

## Project Structure

- `/src`: Source code for the application
- `/tests`: Unit and integration tests
- `/docs`: Additional documentation
- `/examples`: Example usage and implementations
- `Dockerfile`: For containerized deployment
- `requirements.txt`: Python dependencies

## API Capabilities

The Anthropic Computer Use API enables the following functionalities:

1. Screen Capture: Capture and analyze screen content in real-time.
2. Keyboard and Mouse Control: Simulate user inputs for testing and automation.
3. File System Access: Read, write, and manage files within permitted directories.
4. Application Interaction: Launch, close, and interact with macOS applications.
5. System Information Retrieval: Access relevant system data and settings.

## M2 MacBook Specific Optimizations

- Utilizes the M2 chip's Neural Engine for enhanced AI processing capabilities.
- Implements energy-efficient routines to maximize battery life during API operations.
- Leverages the M2's unified memory architecture for faster data processing and reduced latency.

## Security Considerations

- The application runs in a sandboxed environment to prevent unauthorized access to sensitive data.
- User confirmation is required for critical actions to ensure safety and prevent unintended operations.
- Regular security audits and updates will be performed to maintain the integrity of the system.
- Implements macOS-specific security features to ensure compatibility with Apple's security model.

## References

- [Anthropic Computer Use API Documentation](https://docs.anthropic.com/en/docs/build-with-claude/computer-use)
- [Apple M2 Chip Documentation](https://www.apple.com/mac/m2/)

## Contributing

Contributions are welcome! Please read the CONTRIBUTING.md file for guidelines on how to submit pull requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
