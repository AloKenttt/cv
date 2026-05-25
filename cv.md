# Nikita Sakovich

## Contact Information
- **Phone:** +375 (33) 900-25-13
- **E-mail:** nikita.sakovich.ggvp@gmail.com
- **GitHub:** (https://github.com/AloKenttt)

## About Me
I am a highly motivated and detail-oriented individual with a strong passion for web development. My goal is to start a career as a Junior Frontend Developer and contribute to creating user-friendly applications. I have good organizational skills, I am eager to learn new technologies, and I am a fast learner. Even without commercial experience, I am dedicated to improving my coding skills every day and ready to face challenging tasks.

## Skills
- **Programming Languages:** HTML, CSS, JavaScript (Basic)
- **Frameworks and Libraries:** React (currently learning)
- **Tools:** Git, GitHub, VS Code
- **Methodologies:** Agile, Scrum (Basic understanding)

## Code Example
Here is a simple C++ function that checks if a number is prime:

#include <iostream>
#include <cmath>
using namespace std;

bool isPrime(int n) {
    if (n <= 1) return false;
    if (n <= 3) return true;
    if (n % 2 == 0 || n % 3 == 0) return false;

    for (int i = 5; i * i <= n; i += 6) {
        if (n % i == 0 || n % (i + 2) == 0)
            return false;
    }
    return true;
}

int main() {
    int number = 29;
    if (isPrime(number))
        cout << number << " is a prime number." << std::endl;
    else
        cout << number << " is not a prime number." << std::endl;

    return 0;
}
\```
