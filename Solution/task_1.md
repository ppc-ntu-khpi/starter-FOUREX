## Завдання 1. Створення та запуск першої програми (сорочки)
 Код програми
```java
public class Shirt {
    public int shirtID = 25565; // стандартне значення номера моделі сорочки
    public String description = "Сорочка, лол"; // стандартний опис сорочки
    public String color = "Black"; // Колір сорочки
    public double price = 23.5; // стандартна вартість сорочки
    public int quantityInStock = 70; // стандартна кількість на складі
    
    // цей метод просто виводить всю інформацію про сорочку на екран
    public void displayShirtInformation() {
        System.out.println("Shirt ID: " + shirtID);
        System.out.println("Shirt description: " + description);
        System.out.println("Color Code: " + color);
        System.out.println("Shirt price: $" + price);
        System.out.println("Quantity in stock: " + quantityInStock);
    } // кінець методу displayShirtInformation
} // кінець опису класу
```
Результат

![](/Solution/images/Shirt.png)
