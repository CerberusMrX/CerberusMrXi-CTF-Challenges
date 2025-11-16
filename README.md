🚩 CerberusMrXi-CTF-Challenges

A collection of original CTF challenges created by CerberusMrX. This repository includes challenges across multiple categories—such as Web, Cryptography, Forensics, and more—ranging from beginner to advanced difficulty levels.

Feel free to play, learn, open issues for feedback, or share your write-ups!

📂 Challenge Categories

The challenges are organized into the following main directories in the repository:
Category	Description	Repository Link
Cryptography	Challenges focused on encryption, decryption, hashing, and cryptanalysis.	Cryptography
Web	Challenges focusing on web application security, including injection, cross-site scripting (XSS), server-side request forgery (SSRF), and more.	Web
Forensics	Awaiting challenges in this category (likely planned).	
Reverse Engineering	Awaiting challenges in this category (likely planned).	

🛠️ Getting Started & Deployment

To run and solve the challenges, you will generally need to clone the repository and deploy the challenge environment using Docker.

    Clone the repository:
    Bash

git clone https://github.com/CerberusMrX/CerberusMrXi-CTF-Challenges.git
cd CerberusMrXi-CTF-Challenges

Navigate to a specific challenge:

    Browse the Web or Cryptography directories.

    Each challenge folder typically contains its own README.md with specific deployment instructions and the challenge prompt.

Deployment (Typical): Most containerized challenges can be launched using Docker Compose from within the specific challenge directory (e.g., Web/challenge_name):
Bash

    # (Inside the specific challenge folder)
    docker compose up -d

📝 Rules and Format

    Flag Format: All flags will have the format: FLAG{...}.

    Difficulty: Challenges range from beginner to advanced. Consult the individual challenge README.md for specific difficulty ratings and score values.

    Issues & Feedback: If you encounter a bug or have a suggestion, please open an issue in the repository.

    Write-ups: Feel free to share links to your write-ups by opening an issue or a pull request.
