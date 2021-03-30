# MonthCalc
Displays the month after selecting the month that you are wanting

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;


class Class1
{
    static Main Void(string[] args)
    {
        int monthNumber = 0;
        string monthName = "";
        Console.Write("Please enter the Month Number");
        monthNumber = Convert.ToInt32(Console.ReadLine());
        if (monthNumber == 1)
        {
            monthName = "January";
        }
        else if (monthNumber == 2)
        {
            monthName = "Feburary";
        }
        else if (monthNumber == 3)
        {
            monthName = "March";
        }
        else if (monthNumber == 4)
        {
            monthName = "April";
        }
        else if (monthNumber == 5)
        {
            monthName = "May";
        }
        else if (monthNumber == 6)
        {
            monthName = "June";
        }
        else if (monthNumber == 7)
        {
            monthName = "July";
        }
        else if (monthNumber == 8)
        {
            monthName = "August";
        }
        else if (monthNumber == 9)
        {
            monthName = "September";
        }
        else if (monthNumber == 10)
        {
            monthName = "October";
        }
        else if (monthNumber == 11)
        {
            monthName = "November";
        }
        else if (monthNumber == 12)
        {
            monthName = "December"; 
        }

        Console.WriteLine("Month is: " + monthName);
        Console.ReadLine();
    }
  }
