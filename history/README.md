# Golang history
Under influence [Tony Hoare. Communicating Sequential Processes](https://en.wikipedia.org/wiki/Communicating_sequential_processes) 1978 г. Rob Pike development
![Glenda Bunny](https://raw.githubusercontent.com/ASUTinc/golanglinks/master/history/500px-Glenda_bunny_mascot_of_plan_9_from_bell_black.jpg | width=233)
* OS: [Plan 9](https://en.wikipedia.org/wiki/Plan_9_from_Bell_Labs) - 1989 г.
    * Created [Alef](https://en.wikipedia.org/wiki/Alef_(programming_language)) programming language
        * Cross-compilation to pseudo assembler
        * Coroutines
        * Pointers as arguments, return types
```Alef
(int, byte*, byte) 
func() 
{ 
    return (10, "hello", ’c’); 
}

void 
main() 
{
    int a; 
    byte* str; 
    byte c; 
    (a, str, c) = func(); 
}
```