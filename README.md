# -BUG-BOUNTY-REPORT-REAL-STYLE-
The application uses hardcoded credentials and performs authentication locally without server-side validation. Impacto: Any attacker with access to the app can bypass authentication via simple guessing or reverse engineering. Passos para reproduzir: Open app Enter username "admin" Enter password "1234" Access granted Severidade: Alta.
