# Debate Simulation Project

This project simulates a debate between two debaters on a given topic. The debate is moderated by a `Moderator`, and the final decision is made by a `JudgeAgent`, `AudienceMember`, and a `ScoringAgent`. The debate history is tracked, and the outcome is determined based on scoring and audience votes.

## Project Structure

- `src/agents/`
  - `DebateAgent.py`: Defines the `DebateAgent` class, responsible for generating responses in favor of or against the topic.
  - `Moderator.py`: Defines the `Moderator` class, responsible for moderating the debate and concluding it.
  - `JudgeAgent.py`: Defines the `JudgeAgent` class, responsible for making the final decision on the debate.
  - `AudienceMember.py`: Defines the `AudienceMember` class, responsible for simulating audience votes.
  - `ScoringAgent.py`: Defines the `ScoringAgent` class, responsible for scoring the debate rounds.

## How to Run

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd <repository-name>
