# VSCode Snippets for C#

![snippets](https://user-images.githubusercontent.com/6662454/167825170-79eeb79e-69aa-4a2c-80be-d94380cac513.gif)


In VSCode Open:
File -> Preferences -> User Snippets -> C#

Pase the csharp.json

## Examples:

### prefix: console-write-line
```C#
Console.WriteLine($"text");
```

### prefix: record
```C#
public record RecordName(string PropertyName);
```

### prefix: copy-record
```C#
var newRecord = oldRecordName with { Prop = "NewValue" };
```

### prefix: async-enumerable
```C#
private static async IAsyncEnumerable<string> GetData()
{
    foreach (var item in items)
        yield return item;
}
```

### prefix: dictionary
```C#
Dictionary<string, string> dict = new();
```
