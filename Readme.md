
C# Indexer:
Indexers allow instances of a class or struct to be indexed just like arrays.
The indexed value can be set or retrieved without explicitly specifying a type or instance member. 
Indexers resemble properties except that their accessors take parameters. +
The following example defines a generic class with simple get and set accessor methods to assign and retrieve values. 
The Program class creates an instance of this class for storing strings.


Points to Remember :
1-An indexer is same as property except that it defined with this keyword with square bracket that takes paramter.
2-Indexer can be override by having different types of parameters.
3-Ref and out parameter with the indexer is not supported.
4-Indexer can be included as an interface member.
5-Use code snippet to insert indexer syntax automatically in the visual studio

Insert Indexer Code snippet in VisualStudio:
Vsual studio provides shortcut way to insert a code snippet for an indexer so that you don't have to write entire syntax manually.
To insert a snippet for an indexer in Visual Studio, write idexer and press tab or do right click
(or Ctrl + K,S) -> select "Insert Snippet.." -> select "Visual C#.." -> select "indexer".

http://www.tutorialsteacher.com/csharp/csharp-indexer
