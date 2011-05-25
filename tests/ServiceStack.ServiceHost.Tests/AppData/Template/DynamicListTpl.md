# @model.FirstName Dynamic Markdown Template

Hello @model.FirstName,

  * @model.LastName
  * @model.FirstName

# heading 1

@foreach (var link in model.Links) {
  - @link.Name - @link.Href
}

## heading 2

This is a [servicestack.net link](http://www.servicestack.net)

### heading 3
