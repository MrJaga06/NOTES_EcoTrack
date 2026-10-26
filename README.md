<div align="center">

  # 🌱 EcoTrack

  **AI-Powered Sustainability Assistant**

  Making environmental knowledge accessible through AI-powered guidance.

</div>

## About the Project

EcoTrack is an AI-powered web application designed to help people explore environmental sustainability and discover practical ways to adopt eco-friendly habits.

The project aims to make sustainability information easier to access through an interactive interface powered by Google's Gemini API.

## Problem Statement

Many people find it difficult to translate general environmental awareness into practical everyday actions. Accessible digital tools can help people understand sustainability topics, explore responsible consumption, and discover ways to reduce their environmental impact.

## Key Features

- Interactive web-based interface.
- AI-assisted sustainability guidance.
- Gemini API integration.
- Accessible environmental information.

*Update this list to reflect the features implemented in the current application.*

## Technology Stack

- **Frontend:** React and TypeScript
- **Build tool:** Vite
- **AI integration:** Google Gemini API
- **Runtime and package management:** Node.js and npm

Verify these technologies against the project's actual dependencies before submitting.

## Getting Started

### Prerequisites

- Node.js and npm.
- A Google Gemini API key.
- Git.

### Installation

Clone the repository:

```bash
git clone https://github.com/MrJaga06/NOTES_EcoTrack.git
cd NOTES_EcoTrack
```

Install the dependencies:

```bash
npm install
```

### Environment Configuration

Create a `.env.local` file in the project root:

```env
GEMINI_API_KEY=your_gemini_api_key_here
```

Replace the placeholder with your own API key.

**Security:** Never commit your actual API key to GitHub. If the frontend accesses Gemini directly, the key may be exposed in the browser bundle. For a public deployment, consider using a backend to protect the key.

### Run the Application

Start the development server:

```bash
npm run dev
```

Open the local address printed in your terminal.

### Available Scripts

Check `package.json` for the scripts supported by your project. Document the actual commands here.

## Technical Documentation

The following documents describe the application's architecture, sample inputs, and test scenarios.

- [Technical Design Document](docs/TECHNICAL_DESIGN.md)
- [Architecture Diagram](docs/architecture.png)
- [Sample Data](sample-data/sample-activities.json)
- [Test Cases](tests/test-cases.md)

These documents must be added to the repository before their links will work.

## Testing

Testing should cover the application's main user flows, including:

- Successful application startup.
- Submission of a sustainability-related query.
- Handling of empty input.
- Handling of API failures.
- Handling of missing API configuration.

Document the actual results in `tests/test-cases.md`. Do not mark tests as passed until they have been run.

## Responsible AI and Limitations

AI-generated responses may contain inaccurate or incomplete information. Users should verify important environmental claims against reliable sources.

Any numerical carbon-footprint estimates must use documented emission factors and clearly stated assumptions. Do not treat general AI responses as scientifically validated environmental measurements.

## Future Improvements

- Expanded sustainability recommendations.
- Automated tests for core functionality.
- Improved accessibility and error handling.
- Evidence-based environmental impact calculations, if implemented.

## License

See the [`LICENSE`](LICENSE) file for the terms under which this project may be used, modified, and distributed.
