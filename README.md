# Lesson-10
Qovluq ve fayllartla is

# Reading Materials <br />
1 - https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/file-system/ (Sol menuda File system and the registry chapterinde olan artikllari oxuyub tanish olun)<br />
2 - https://zetcode.com/csharp/directory/ <br />
3 - https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types/generics <br />
4 - https://www.geeksforgeeks.org/c-sharp-generics-introduction/ <br />
5 - https://dev.to/adavidoaiei/fundamental-data-structures-and-algorithms-in-c-4ocf <br />
6 - https://stackoverflow.com/questions/128636/net-data-structures-arraylist-list-hashtable-dictionary-sortedlist-sorted <br />

Tasks: <br />
1- Write a program in C# Sharp to create and read the last line of a file.
Test Data:
Input number of lines to write in the file :3
Input 3 strings below :
Input line 1 : line1
Input line 2 : line2
Input line 3 : line3

Expected Output:

The content of the last line of the file mytest.txt is: line3 <br />

2- Write a program to calculate all files and directories count in a given directory (including files and folder in any subdirectory) <br />

3- Create new MyList class from scratch, which work mostly as List. It hsould have void Add(T item), void Remove(T item), void Clear(), bool Contains(T item) methods and Count poperty. We also can iterate this collection via foreach  <br />

4 - Finish TODO section:

public static List<string> ProcessToKill(List<string> process)
{
    // Create list of string with initial size to 3.
    List<string> processToKill = new List<string>(3);

    // Show capacity ; here : 3.
    Console.WriteLine(string.Format("Capacity {0}", processToKill.Capacity));

    // Show number of items ; here : 0.
    Console.WriteLine(string.Format("Count {0}", processToKill.Count));

    /// TODO: 
    /// Add items from process to processToKill list 
    /// Process equals "Explorer.exe" don't be added, ignore it

    foreach (var p in processToKill)
    {
        Console.WriteLine(p);
    }           

    return processToKill;
}

5 - Please remove the item with the key 'Han' from the dictionary:

using System; <br />
using System.Collections.Generic; <br />

public class Program <br />
{ <br />
    public static void Main() <br />
    { <br />
        Dictionary<string, bool> characters = new Dictionary<string, bool>() <br />
        { <br />
            { "Luke", true }, <br />
            { "Han", false }, <br />
            { "Chewbacca", false } <br />
        }; <br />

        // Your code here.
    } <br />
} <br />


