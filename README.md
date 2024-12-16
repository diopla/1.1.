# 1.1.
5

#include <iostream>
#include <string>

using namespace std;
 
class Book
{
    string name;
    string author;
    int age;

public:
    Book(const string name, const string author, int age)
        : name(name), author(author), age(age) {}

    void displayInfo() const {
        cout << name << endl;
        cout << author << endl;
        cout << age << endl;
    }

    void changeAuthor(const string newAuthor) {
        author = newAuthor;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Book book("Леонов", "Саша", 2025);
    book.displayInfo();
    book.changeAuthor("Саня");
    cout << "\nИзменения:\n";
    book.displayInfo();
}

6

#include <iostream>
#include <string>

using namespace std;
 
class Car
{
    string brand;
    string model;
    int age;

public:
    Car(const string brand, const string model, int age)
        : brand(brand), model(model), age(age) {}

    void displayInfo() const {
        cout << brand << endl;
        cout << model << endl;
        cout << age << endl;
    }

    void changeBrand(const string newBrand) {
        brand = newBrand;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Car car("Пежо", "1", 2008);
    car.displayInfo();
    car.changeBrand("Мазда");
    cout << "\nИзменения:\n";
    car.displayInfo();
}

7

#include <iostream>
#include <string>

using namespace std;
 
class User
{
    string name;
    string surname;
    int login;

public:
    User(const string name, const string surname, int login)
        : name(name), surname(surname), login(login) {}

    void displayInfo() const {
        cout << name << endl;
        cout << surname << endl;
        cout << login << endl;
    }

    void changeLogin(int newLogin) {
        login = newLogin;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    User user("Саша", "Леонов", 2005);
    user.displayInfo();
    user.changeLogin(2006);
    cout << "\nИзменения:\n";
    user.displayInfo();
}

8

#include <iostream>
#include <string>

using namespace std;
 
class Product
{
    string name;
    int price;
    int quantity;

public:
    Product(const string name,int price, int quantity)
        : name(name), price(price), quantity(quantity) {}

    void displayInfo() const {
        cout << name << endl;
        cout << price << endl;
        cout << quantity << endl;
    }

    void changePrice(int newPrice) {
        price = newPrice;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Product product("Саня", 5999, 45);
    product.displayInfo();
    product.changePrice(7999);
    cout << "\nИзменения:\n";
    product.displayInfo();
}

9

#include <iostream>
#include <string>

using namespace std;
 
class Teacher
{
    string name;
    string surname;
    string subject;

public:
    Teacher(const string name,const string surname, const string subject)
        : name(name), surname(surname), subject(subject) {}

    void displayInfo() const {
        cout << name << endl;
        cout << surname << endl;
        cout << subject << endl;
    }

    void changeSubject(const string newSubject) {
        subject = newSubject;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Teacher teacher("Александер", "Леонов", "Физика");
    teacher.displayInfo();
    teacher.changeSubject("Химия");
    cout << "\nИзменения:\n";
    teacher.displayInfo();
}

10

#include <iostream>
#include <string>

using namespace std;

class Client
{
    string name;
    string surname;
    int age;

public:
    Client(const string name, const string surname, int age)
        : name(name), surname(surname), age(age) {}

    void displayInfo() const {
        cout << name << endl;
        cout << surname << endl;
        cout << age << endl;
    }

    void changeName(const string newName) {
        name = newName;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Client client("Саша", "Леонов", 18);
    client.displayInfo();
    client.changeName("Саня");
    cout << "\nИзменения:\n";
    client.displayInfo();
}

11

#include <iostream>
#include <string>

using namespace std;

class Shop
{
    string name;
    string adress;
    int quantity;

public:
    Shop(const string name, const string adress, int quantity)
        : name(name), adress(adress), quantity(quantity) {}

    void displayInfo() const {
        cout << name << endl;
        cout << adress << endl;
        cout << quantity << endl;
    }

    void changeQuantity(int newQuantity) {
        quantity = newQuantity;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Shop shop("Супер", "Калинина3", 454);
    shop.displayInfo();
    shop.changeQuantity(545);
    cout << "\nИзменения:\n";
    shop.displayInfo();
}

12

#include <iostream>
#include <string>

using namespace std;

class Bank
{
    string name;
    string adress;
    int quantity;

public:
    Bank(const string name, const string adress, int quantity)
        : name(name), adress(adress), quantity(quantity) {}

    void displayInfo() const {
        cout << name << endl;
        cout << adress << endl;
        cout << quantity << endl;
    }

    void changeQuantity(int newQuantity) {
        quantity = newQuantity;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Bank bank("Пять звезд", "Калинина 9", 453534);
    bank.displayInfo();
    bank.changeQuantity(353);
    cout << "\nИзменения:\n";
    bank.displayInfo();
}

13

#include <iostream>
#include <string>

using namespace std;

class University
{
    string name;
    string adress;
    int number_of_students;

public:
    University(const string name, const string adress, int number_of_students)
        : name(name), adress(adress), number_of_students(number_of_students) {}

    void displayInfo() const {
        cout << name << endl;
        cout << adress << endl;
        cout << number_of_students << endl;
    }

    void changeТumber_of_students(int newNumber_of_students) {
        number_of_students = newNumber_of_students;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    University university("Неизвестный", "Калинина 345", 45);
    university.displayInfo();
    university.changeТumber_of_students(390);
    cout << "\nИзменения:\n";
    university.displayInfo();
}

14

#include <iostream>
#include <string>

using namespace std;

class Sсhool
{
    string name;
    string adress;
    int number_of_students;

public:
    Sсhool(const string name, const string adress, int number_of_students)
        : name(name), adress(adress), number_of_students(number_of_students) {}

    void displayInfo() const {
        cout << name << endl;
        cout << adress << endl;
        cout << number_of_students << endl;
    }

    void changeNumber_of_students(int newNumber_of_students) {
        number_of_students = newNumber_of_students;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Sсhool sсhool("Неизвестнfz", "Калинина 999", 456);
    sсhool.displayInfo();
    sсhool.changeNumber_of_students(496);
    cout << "\nИзменения:\n";
    sсhool.displayInfo();
}

15

#include <iostream>
#include <string>

using namespace std;

class Library
{
    string name;
    string adress;
    int number_of_book;

public:
    Library(const string name, const string adress, int number_of_book)
        : name(name), adress(adress), number_of_book(number_of_book) {}

    void displayInfo() const {
        cout << name << endl;
        cout << adress << endl;
        cout << number_of_book << endl;
    }

    void changeNumber_of_book(int newNumber_of_book) {
        number_of_book = newNumber_of_book;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Library library("Неизвестная", "Калинина 666", 345645646);
    library.displayInfo();
    library.changeNumber_of_book(848554);
    cout << "\nИзменения:\n";
    library.displayInfo();
}

16

#include <iostream>
#include <string>

using namespace std;

class Museum
{
    string name;
    string adress;
    int number_of_exhibits;

public:
    Museum(const string name, const string adress, int number_of_exhibits)
        : name(name), adress(adress), number_of_exhibits(number_of_exhibits) {}

    void displayInfo() const {
        cout << name << endl;
        cout << adress << endl;
        cout << number_of_exhibits << endl;
    }

    void changeNumber_of_exhibits(int newNumber_of_exhibits) {
        number_of_exhibits = newNumber_of_exhibits;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Museum museum("Неизвестный", "Калинина 777", 32);
    museum.displayInfo();
    museum.changeNumber_of_exhibits(12);
    cout << "\nИзменения:\n";
    museum.displayInfo();
}

17

#include <iostream>
#include <string>

using namespace std;

class Theater
{
    string name;
    string adress;
    int number_of_performances;

public:
    Theater(const string name, const string adress, int number_of_performances)
        : name(name), adress(adress), number_of_performances(number_of_performances) {}

    void displayInfo() const {
        cout << name << endl;
        cout << adress << endl;
        cout << number_of_performances << endl;
    }

    void changeNumber_of_performances(int newNumber_of_performances) {
        number_of_performances = newNumber_of_performances;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Theater theater("Неизвестный", "Калинина 98", 789);
    theater.displayInfo();
    theater.changeNumber_of_performances(678);
    cout << "\nИзменения:\n";
    theater.displayInfo();
}

18

#include <iostream>
#include <string>

using namespace std;

class Сinema
{
    string name;
    string adress;
    int number_of_movies;

public:
    Сinema(const string name, const string adress, int number_of_movies)
        : name(name), adress(adress), number_of_movies(number_of_movies) {}

    void displayInfo() const {
        cout << name << endl;
        cout << adress << endl;
        cout << number_of_movies << endl;
    }

    void changeNumber_of_movies(int newNumber_of_movies) {
        number_of_movies = newNumber_of_movies;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Сinema cinema("Неизвестный", "Калинина 55", 15);
    cinema.displayInfo();
    cinema.changeNumber_of_movies(21);
    cout << "\nИзменения:\n";
    cinema.displayInfo();
}

19

#include <iostream>
#include <string>

using namespace std;

class Restaurant
{
    string name;
    string adress;
    int number_of_dishes;

public:
    Restaurant(const string name, const string adress, int number_of_dishes)
        : name(name), adress(adress), number_of_dishes(number_of_dishes) {}

    void displayInfo() const {
        cout << name << endl;
        cout << adress << endl;
        cout << number_of_dishes << endl;
    }

    void changeNumber_of_dishes(int newNumber_of_dishes) {
        number_of_dishes = newNumber_of_dishes;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Restaurant restaurant("Неизвестный", "Калинина 6", 122);
    restaurant.displayInfo();
    restaurant.changeNumber_of_dishes(212);
    cout << "\nИзменения:\n";
    restaurant.displayInfo();
}

20

#include <iostream>
#include <string>

using namespace std;

class Сafe
{
    string name;
    string adress;
    int number_of_rooms;

public:
    Сafe(const string name, const string adress, int number_of_rooms)
        : name(name), adress(adress), number_of_rooms(number_of_rooms) {}

    void displayInfo() const {
        cout << name << endl;
        cout << adress << endl;
        cout << number_of_rooms << endl;
    }

    void changeNumber_of_rooms(int newNumber_of_rooms) {
        number_of_rooms = newNumber_of_rooms;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Сafe cafe("Неизвестный", "Калинина 5443", 6346456);
    cafe.displayInfo();
    cafe.changeNumber_of_rooms(215542);
    cout << "\nИзменения:\n";
    cafe.displayInfo();
}

21

#include <iostream>
#include <string>

using namespace std;

class Hotel
{
    string name;
    string adress;
    int number_of_rooms;

public:
    Hotel(const string name, const string adress, int number_of_rooms)
        : name(name), adress(adress), number_of_rooms(number_of_rooms) {}

    void displayInfo() const {
        cout << name << endl;
        cout << adress << endl;
        cout << number_of_rooms << endl;
    }

    void changeNumber_of_rooms(int newNumber_of_rooms) {
        number_of_rooms = newNumber_of_rooms;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Hotel hotel("Неизвестный", "Калинина 43", 4544);
    hotel.displayInfo();
    hotel.changeNumber_of_rooms(3442);
    cout << "\nИзменения:\n";
    hotel.displayInfo();
}

22

#include <iostream>
#include <string>

using namespace std;

class Airport
{
    string name;
    string adress;
    int number_of_flights;

public:
    Airport(const string name, const string adress, int number_of_flights)
        : name(name), adress(adress), number_of_flights(number_of_flights) {}

    void displayInfo() const {
        cout << name << endl;
        cout << adress << endl;
        cout << number_of_flights << endl;
    }

    void changeNumber_of_flights(int newNumber_of_flights) {
        number_of_flights = newNumber_of_flights;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Airport airport("Неизвестный", "Калинина 343", 4);
    airport.displayInfo();
    airport.changeNumber_of_flights(2);
    cout << "\nИзменения:\n";
    airport.displayInfo();
}

23

#include <iostream>
#include <string>

using namespace std;

class Railway_station
{
    string name;
    string adress;
    int number_of_trains;

public:
    Railway_station(const string name, const string adress, int number_of_trains)
        : name(name), adress(adress), number_of_trains(number_of_trains) {}

    void displayInfo() const {
        cout << name << endl;
        cout << adress << endl;
        cout << number_of_trains << endl;
    }

    void changeNumber_of_trains(int newNumber_of_trains) {
        number_of_trains = newNumber_of_trains;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Railway_station railway_station("Неизвестный", "Калинина 1", 4);
    railway_station.displayInfo();
    railway_station.changeNumber_of_trains(5);
    cout << "\nИзменения:\n";
    railway_station.displayInfo();
}

24

#include <iostream>
#include <string>

using namespace std;

class Bus_station
{
    string name;
    string adress;
    int number_of_buses;

public:
    Bus_station(const string name, const string adress, int number_of_buses)
        : name(name), adress(adress), number_of_buses(number_of_buses) {}

    void displayInfo() const {
        cout << name << endl;
        cout << adress << endl;
        cout << number_of_buses << endl;
    }

    void changeNumber_of_buses(int newNumber_of_buses) {
        number_of_buses = newNumber_of_buses;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Bus_station bus_station("Неизвестный", "Калинина 99999", 12);
    bus_station.displayInfo();
    bus_station.changeNumber_of_buses(15);
    cout << "\nИзменения:\n";
    bus_station.displayInfo();
}

25

#include <iostream>
#include <string>

using namespace std;

class Park
{
    string name;
    string adress;
    int number_of_trees;

public:
    Park(const string name, const string adress, int number_of_trees)
        : name(name), adress(adress), number_of_trees(number_of_trees) {}

    void displayInfo() const {
        cout << name << endl;
        cout << adress << endl;
        cout << number_of_trees << endl;
    }

    void changeNumber_of_trees(int newNumber_of_trees) {
        number_of_trees = newNumber_of_trees;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Park park("Неизвестный", "Калинина 2", 3445435646467675);
    park.displayInfo();
    park.changeNumber_of_trees(0);
    cout << "\nИзменения:\n";
    park.displayInfo();
}

26

#include <iostream>
#include <string>

using namespace std;

class Garden
{
    string name;
    string adress;
    int number_of_flowers;

public:
    Garden(const string name, const string adress, int number_of_flowers)
        : name(name), adress(adress), number_of_flowers(number_of_flowers) {}

    void displayInfo() const {
        cout << name << endl;
        cout << adress << endl;
        cout << number_of_flowers << endl;
    }

    void changeNumber_of_flowers(int newNumber_of_flowers) {
        number_of_flowers = newNumber_of_flowers;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Garden garden("Неизвестный", "Калинина 2", 3445435675);
    garden.displayInfo();
    garden.changeNumber_of_flowers(54540);
    cout << "\nИзменения:\n";
    garden.displayInfo();
}

27

#include <iostream>
#include <string>

using namespace std;

class Zoo
{
    string name;
    string adress;
    int number_of_animals;

public:
    Zoo(const string name, const string adress, int number_of_animals)
        : name(name), adress(adress), number_of_animals(number_of_animals) {}

    void displayInfo() const {
        cout << name << endl;
        cout << adress << endl;
        cout << number_of_animals << endl;
    }

    void changeNumber_of_animals(int newNumber_of_animals) {
        number_of_animals = newNumber_of_animals;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Zoo zoo("Неизвестный", "Калинина 3", 35);
    zoo.displayInfo();
    zoo.changeNumber_of_animals(40);
    cout << "\nИзменения:\n";
    zoo.displayInfo();
}

28

#include <iostream>
#include <string>

using namespace std;

class Aquarium
{
    string name;
    string adress;
    int number_of_fish;

public:
    Aquarium(const string name, const string adress, int number_of_fish)
        : name(name), adress(adress), number_of_fish(number_of_fish) {}

    void displayInfo() const {
        cout << name << endl;
        cout << adress << endl;
        cout << number_of_fish << endl;
    }

    void changeNumber_of_fish(int newNumber_of_fish) {
        number_of_fish = newNumber_of_fish;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Aquarium aquarium("Неизвестный", "Калинина 4", 76);
    aquarium.displayInfo();
    aquarium.changeNumber_of_fish(77);
    cout << "\nИзменения:\n";
    aquarium.displayInfo();
}

29

#include <iostream>
#include <string>

using namespace std;

class Art_museum
{
    string name;
    string adress;
    int number_of_exhibits;

public:
    Art_museum(const string name, const string adress, int number_of_exhibits)
        : name(name), adress(adress), number_of_exhibits(number_of_exhibits) {}

    void displayInfo() const {
        cout << name << endl;
        cout << adress << endl;
        cout << number_of_exhibits << endl;
    }

    void changeNumber_of_exhibits(int newNumber_of_exhibits) {
        number_of_exhibits = newNumber_of_exhibits;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Art_museum art_museum("Неизвестный", "Калинина 5", 6);
    art_museum.displayInfo();
    art_museum.changeNumber_of_exhibits(7);
    cout << "\nИзменения:\n";
    art_museum.displayInfo();
}

30

#include <iostream>
#include <string>

using namespace std;

class Opera_house
{
    string name;
    string adress;
    int number_of_exhibits;

public:
    Opera_house(const string name, const string adress, int number_of_exhibits)
        : name(name), adress(adress), number_of_exhibits(number_of_exhibits) {}

    void displayInfo() const {
        cout << name << endl;
        cout << adress << endl;
        cout << number_of_exhibits << endl;
    }

    void changeNumber_of_exhibits(int newNumber_of_exhibits) {
        number_of_exhibits = newNumber_of_exhibits;
    }
};

int main()
{
    setlocale(LC_ALL, "RU");
    Opera_house opera_house("Неизвестный", "Калинина 6", 34);
    opera_house.displayInfo();
    opera_house.changeNumber_of_exhibits(73);
    cout << "\nИзменения:\n";
    opera_house.displayInfo();
}
