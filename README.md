# Intro-to-Functions

SLIDE 11, Declaring and Defining

    #include <iostream>
    using namespace std; 

    void welcome(); //function declaration

    int main() {
        welcome(); //function call
        return 0;
    }

    void welcome() { //function definition

        cout << "Welcome to BSU" << endl;
    }

SLIDE 12, You say hello, I say goodbye

    #include <iostream>
    using namespace std;

    void first() {
        cout << "Welcome" << endl;
    }

    void second() {
        cout << "End of program" << endl;
    }

    int main()
    {
        first();
        second();
    }
