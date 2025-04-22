[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/W2_TH6Rw)
![830004F5-A2AD-4D9C-BA3F-7FD4C038E464](https://github.com/user-attachments/assets/8090c111-4015-4ebf-9dfa-129146c12405)
![5860D731-1E48-47B3-B74B-DC2B3B0E9025](https://github.com/user-attachments/assets/2a06aa32-4c95-49a4-9b11-7e4dc6c30252)
![52D67AB8-43FC-46FC-925C-143ED4FF642F](https://github.com/user-attachments/assets/1e2b4f4b-3d89-4f2d-82bf-5a8670f81fea)
﻿namespace ThemeParkCalculationTask
{
    internal class Program
    {
        static void Main(string[] args)
        {
            /* A theme park charges £15 per person for a daily ticket. If there are six or more people in a group, the group is given a £5 discount.
               Write a C# program to calculate the total charge for a group of people visiting the theme park.
               The program must:
                • get the user to enter the number of people in a group
                • calculate the total charge by:
                    ○ charging £15 per person
                    ○ reducing the total charge by £5 if there are six or more people
                • output the total charge.
            You should use meaningful variable name(s) inyour answer.
            */
            // Write your program and test it with the following test data
            // 1: 4 people
            // 2: 10 people
            // 3: 6 people
            // Commit your changes and add screnshot evidence of your program running to the Readme
Console.WriteLine("How many people are in the group?");
    int numOfPeople = Convert.ToInt32(Console.ReadLine());
    double charge = numOfPeople * 15;
    if (numOfPeople > 5){
        charge = charge - 5;
        }
            Console.WriteLine("The total charge is £" + charge);
        }
    }
}
