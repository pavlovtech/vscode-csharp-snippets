# VSCode Snippets for C#

Examples:

## prefix: console-write-line
```C#
Console.WriteLine($"text");
```

## prefix: record
```C#
public record RecordName(string PropertyName);
```

## prefix: copy-record
```C#
var newRecord = oldRecordName with { Prop = "NewValue" };
```

## prefix: async-enumerable
```C#
private static async IAsyncEnumerable<string> GetData()
{
    foreach (var item in items)
        yield return item;
}
```

## prefix: dictionary
```C#
Dictionary<string, string> dict = new();
```
