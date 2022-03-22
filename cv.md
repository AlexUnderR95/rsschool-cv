**Alexander Shmidt**
===
**Contacts:**
---
* **Location:** Saratov, Russia.
* **Phone Number:** +7(927)050-43-89
* **Email:** worldfoner@gmail.com
* **GitHub:** AlexUnderR95

**About Me:**
---
 * Open to new knowledge and fast learner
 * Communicable and non-conflicting
 

**Skills:**
---
* HTML5,CSS3
* JavaScript Basics, C# Bascs
* Git, GitHub
* VS Code, VS community
* Adobe Photoshop, Premiere pro, Blender, 3DMax

**Code Example:**
---
The following code example contains a console program for finding the minimum value in an array and for finding the sum of even numbers in an array based on C#
```
{
        static void Main(string[] args)
        {
            int sumOfEvenNumber = 0;
            Console.Write("Enter the number of array elements:\t");
            
            int elementCount = int.Parse(Console.ReadLine());
           
            int[] myArray = new int[elementCount];

            for (int i = 0; i < myArray.Length; i++)
            {
                Console.Write($"Enter array element with index {i}:\t ");
                myArray[i] = int.Parse(Console.ReadLine());
            }
            int min = myArray[0];

            for (int i = 0; i < myArray.Length; i++)
            {
                if (myArray[i] % 2 == 0)
                {
                    sumOfEvenNumber = sumOfEvenNumber + myArray[i];
                }
                if (myArray[i] < min)
                {
                    min = myArray[i];
                }
            }

            Console.WriteLine("Your Array");

            for (int i = myArray.Length - 1; i >= 0; i--)
            {
                Console.WriteLine(myArray[i]);
            }
            Console.WriteLine("Sum of even numbers: " + sumOfEvenNumber);

            Console.WriteLine("Min number in array: " + min);

            Console.ReadLine();
        }
    }
}
```
**Education:**
---
 * Saratov State University named after Chernyshevsky. Faculty of Nonlinear Processes (2 years)
 * C# course by lessons on YouTube from #SimpleCode
 * Basics of HTML, CSS, JS (https://ru.code-basics.com/)

**English:**
---
English level B1 (From time to time I communicate with my foreign friends)
