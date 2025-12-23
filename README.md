<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>TravelPlanner-multiAgent</title>
</head>

<body style="font-family: Arial, Helvetica, sans-serif; line-height: 1.6; color: #1f2937; background-color: #ffffff; padding: 20px;">

  <h1 style="color: #0e75b6;">TravelPlanner-multiAgent ✈️</h1>

  <p style="font-size: 16px;">
    <strong>TravelPlanner-multiAgent</strong> is a Python-based multi-agent travel planning system that helps users build
    personalized travel itineraries by coordinating multiple intelligent agents such as a destination recommender,
    schedule optimizer, and budget manager.
  </p>

  <p style="font-size: 16px;">
    This project is designed for <strong>research, experimentation, and prototype applications</strong> in
    multi-agent coordination, automated itinerary generation, and AI-powered travel assistance.
  </p>

  <hr style="border: 1px solid #e5e7eb; margin: 30px 0;" />

  <h2 style="color: #111827;">✨ Features</h2>
  <ul style="font-size: 15px;">
    <li>Multi-agent architecture with modular responsibilities (recommendation, scheduling, budgeting, routing)</li>
    <li>Configurable inputs: destinations, dates, budgets, and user preferences</li>
    <li>Itinerary optimization considering time, cost, and user priorities</li>
    <li>Extensible codebase for adding new agents and integration points (APIs, UIs)</li>
  </ul>

  <hr style="border: 1px solid #e5e7eb; margin: 30px 0;" />

  <h2 style="color: #111827;">🛠 Requirements</h2>
  <ul style="font-size: 15px;">
    <li>Python 3.8+</li>
    <li>pandas</li>
    <li>numpy</li>
    <li>requests</li>
    <li>networkx</li>
  </ul>

  <hr style="border: 1px solid #e5e7eb; margin: 30px 0;" />

  <h2 style="color: #111827;">⚙️ Installation</h2>

  <p><strong>1. Clone the repository</strong></p>
  <pre style="background-color: #f3f4f6; padding: 12px; border-radius: 6px;">
git clone https://github.com/Yasas-Samaraweera/TravelPlanner-multiAgent.git
cd TravelPlanner-multiAgent
  </pre>

  <p><strong>2. Create and activate a virtual environment</strong></p>
  <pre style="background-color: #f3f4f6; padding: 12px; border-radius: 6px;">
python -m venv venv
source venv/bin/activate   # macOS / Linux
venv\Scripts\activate      # Windows
  </pre>

  <p><strong>3. Install dependencies</strong></p>
  <pre style="background-color: #f3f4f6; padding: 12px; border-radius: 6px;">
pip install -r requirements.txt
  </pre>

  <hr style="border: 1px solid #e5e7eb; margin: 30px 0;" />

  <h2 style="color: #111827;">▶️ Usage</h2>

  <p>
    Run the main planner using a configuration file:
  </p>

  <pre style="background-color: #f3f4f6; padding: 12px; border-radius: 6px;">
python main.py --config configs/sample_config.yaml
  </pre>

  <p style="font-size: 15px;">
    Configuration files define destinations, travel dates, budget constraints, and user preferences.
    The system coordinates multiple agents to generate an optimized travel itinerary.
  </p>

  <hr style="border: 1px solid #e5e7eb; margin: 30px 0;" />

  <h2 style="color: #111827;">🧠 Project Structure</h2>

  <pre style="background-color: #f3f4f6; padding: 12px; border-radius: 6px;">
TravelPlanner-multiAgent/
│
├── agents/        # Agent implementations (recommender, scheduler, budget manager)
├── core/          # Multi-agent coordination and orchestration logic
├── data/          # Sample datasets and configuration files
├── tests/         # Unit and integration tests
├── main.py        # Entry point
└── requirements.txt
  </pre>

  <hr style="border: 1px solid #e5e7eb; margin: 30px 0;" />

  <h2 style="color: #111827;">🧪 Testing</h2>

  <p>Run tests using:</p>
  <pre style="background-color: #f3f4f6; padding: 12px; border-radius: 6px;">
pytest
  </pre>

  <hr style="border: 1px solid #e5e7eb; margin: 30px 0;" />

  <h2 style="color: #111827;">🤝 Contributing</h2>

  <p style="font-size: 15px;">
    Contributions are welcome! Please open issues for bug reports or feature requests.
    Submit pull requests with appropriate tests and documentation for significant changes.
  </p>

  <hr style="border: 1px solid #e5e7eb; margin: 30px 0;" />

  <h2 style="color: #111827;">📄 License</h2>

  <p style="font-size: 15px;">
    This project is licensed under the <strong>MIT License</strong>.
    You may add a LICENSE file to the repository if not already included.
  </p>

  <hr style="border: 1px solid #e5e7eb; margin: 30px 0;" />

  <p style="font-size: 14px; color: #6b7280;">
    Developed by <strong>Yasas Samaraweera</strong> • Multi-Agent Systems • AI/ML Engineering
  </p>

</body>
</html>


