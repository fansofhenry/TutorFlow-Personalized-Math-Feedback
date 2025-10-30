# TutorFlow-Personalized-Math-Feedback
Build a simple, open-source prototype that gives adaptive feedback to students learning math (starting with linear algebra concepts).

tutorflow/
│
├── README.md                 # Project overview, goals, how to run
├── app.py                    # Streamlit main app
├── prompts/
│   ├── tutor_prompts.json    # Stored system and user prompts
│   └── vibes.md              # Definitions of tone and interaction styles
├── data/
│   ├── examples.json         # Example math problems + feedback
│   └── student_context.json  # Context memory (user profile, progress)
├── utils/
│   ├── context_engine.py     # Load and format context
│   ├── prompt_engine.py      # Build the prompt dynamically
│   └── vibe_engine.py        # Manage tone and personality
└── requirements.txt
