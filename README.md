 ЛЕКЦИЯ 2
    ЗАДАЧА 2
    ============

    Даны радиус круга и сторона квадрата.
    У какой фигуры площать больше?
 */

import java.util.Scanner;

public class Task2 {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        double circle_radius;
        double side_square;

        System.out.print("Введите радиус круга: ");

        if (sc.hasNextDouble()) { //Проверяем число ли введено
            circle_radius = sc.nextDouble();
            System.out.println("Спасибо! Вы ввели число " + circle_radius);
        }
        else {
            System.out.println("Извините, но это не число. Перезапустите программу и попробуйте снова!");
            circle_radius = 0; //присваиваем любое значение чтобы скомпилировалась программа
            System.exit(1);
