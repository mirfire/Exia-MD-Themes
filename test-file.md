# First Paragraph

- [First Paragraph](#first-paragraph)
  - [Normal Paragraphs](#normal-paragraphs)
  - [Formatting](#formatting)
    - [Emphasis](#emphasis)
    - [Links](#links)
  - [Images](#images)
  - [Lists](#lists)
    - [Unordered List](#unordered-list)
    - [Ordered List](#ordered-list)
    - [Headers](#headers)
- [Header 1](#header-1)
  - [Header 2](#header-2)
    - [Header 3](#header-3)
      - [Header 4](#header-4)
  - [Blocks](#blocks)
      - [JavaScript](#javascript)
      - [C](#c)
      - [Python](#python)
      - [No language](#no-language)
  - [Tables](#tables)
    - [Left aligned columns](#left-aligned-columns)
    - [Center aligned columns](#center-aligned-columns)
    - [Right aligned columns](#right-aligned-columns)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin a feugiat est. Duis eu nunc quis lectus pharetra posuere. Suspendisse fringilla nisl eget erat molestie tincidunt. Suspendisse vulputate laoreet neque, eu ullamcorper sem suscipit ut. Aliquam erat volutpat. Etiam faucibus, nisi eget elementum lobortis, massa quam hendrerit elit, in maximus diam nisi in elit. Aliquam id odio non est luctus commodo. Donec vitae velit maximus, lobortis elit in, egestas justo. Phasellus sed leo vitae ipsum venenatis sodales id in massa. Quisque auctor consectetur auctor. Suspendisse commodo eros neque, at rhoncus neque iaculis id. Aenean quis metus semper, auctor enim ut, vestibulum urna. In vulputate tortor et sem aliquet tempor. Pellentesque consequat orci id diam bibendum eleifend. 

## Normal Paragraphs

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris ultricies libero velit, eget aliquam justo finibus nec. Maecenas a lacinia risus. Fusce tempor efficitur risus vitae ornare. Sed tempor pretium dolor, eget tempor metus porta eu. Pellentesque ultricies ante tortor, vel hendrerit libero facilisis id. Nunc eget justo lacus. Suspendisse laoreet velit sit amet ornare lacinia. Morbi at orci justo. Donec ipsum urna, consequat convallis tincidunt in, condimentum nec eros. Nam eget purus metus. Nulla semper nunc tellus, ac vestibulum lacus dictum malesuada. Sed vitae leo at mauris molestie blandit.

Nulla tempor blandit tellus ut semper. Donec eleifend tortor ut arcu lobortis rutrum. Vivamus pellentesque sodales lorem, at iaculis metus pellentesque nec. In mattis tincidunt mauris. In vel erat ut elit pharetra feugiat at quis lectus. Quisque facilisis aliquet leo, vel sodales lorem maximus quis. Quisque porttitor leo nisl, ut viverra urna porttitor eget. Cras ultricies neque in felis fringilla ullamcorper. Nulla facilisi. Don*

## Formatting

### Emphasis

*This is italic text.*

**This is bold text.**

***This is bold italic text.***

~~This is wrong text.~~

`This is inline code or command.`

### Links

[Link with text](https://github.com/mirfire/Exia-MD-Themes).

[Link with text and title](https://github.com/mirfire/Exia-MD-Themes "title text!").

Simple link <https://github.com/mirfire/Exia-MD-Themes>

## Images

![Minion](https://octodex.github.com/images/minion.png)
![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")

## Lists

### Unordered List

- Lorem ipsum dolor sit amet, consectetur adipiscing elit.
  - Ut sollicitudin velit vel elit fringilla ultrices.
  - Duis ornare ipsum non molestie egestas.
  - Donec eu nisl lacinia, dictum nibh eget, sagittis dolor.
  - Maecenas porta nisl at arcu rutrum, non facilisis turpis pellentesque.

- Lorem ipsum dolor sit amet, consectetur adipiscing elit.
  - Ut sollicitudin velit vel elit fringilla ultrices.
  - Maecenas porta nisl at arcu rutrum, non facilisis turpis pellentesque.

### Ordered List

1. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
2. Ut sollicitudin velit vel elit fringilla ultrices.
3. Duis ornare ipsum non molestie egestas.
4. Donec eu nisl lacinia, dictum nibh eget, sagittis dolor.
5. Maecenas porta nisl at arcu rutrum, non facilisis turpis pellentesque.

### Headers

# Header 1

## Header 2

### Header 3

#### Header 4

##### Header 5

###### Header 6

## Blocks

#### JavaScript

```javascript
function myFunction(name,job) {
    document.getElementById("demo").innerHTML =
    "Welcome " + name + ", the " + job + ".";
}
```

#### C#

```csharp
static void Main(string[] args) {
 int i;

 Console.Write("Enter a Number : ");
 i = int.Parse(Console.ReadLine());
 if (i % 2 == 0) {
  Console.Write("Entered Number is an Even Number");
  Console.Read();
 } else {
  Console.Write("Entered Number is an Odd Number");
  Console.Read();
 }
}
```

#### Python

```python
x = int(input("Please enter an integer: "))
if x < 0:
  x = 0
  print('Negative changed to zero')
elif x == 0:
  print('Zero')
elif x == 1:
  print('Single')
else:
  print('More')
```

#### No language

##### Tab Block

    This is unformatted code.
    It doesn't look very nice.

##### Code Block

```none
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```

## Tables

### Left aligned columns

| Option | Description                                                               |
| ------ | ------------------------------------------------------------------------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default.    |
| ext    | extension to be used for dest files.                                      |

### Center aligned columns

| Option | Description                                                               |
| :----: | :-----------------------------------------------------------------------: |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default.    |
| ext    | extension to be used for dest files.                                      |

### Right aligned columns

| Option | Description                                                               |
| -----: | ------------------------------------------------------------------------: |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default.    |
| ext    | extension to be used for dest files.                                      |
