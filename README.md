```mermaid
classDiagram
  class Book {
    + string name
    # int number
    - List<Page> pages
    + Page getPages(int index)
  }
  
  class Page {
    + string title
    + string body
  }
  Book --> Page
  Book ..> BookService
```
