## Projektstruktur

```plaintext
SOSE-24_SUPERHIRN_14
 ├─src
 │  ├─core
 │  ├─features
 │  │  ├─menu
 │  │  ├─gameboard
 │  │  ├─result
 │  │  ├─scorelist
 │  │  ├─tutorial
 │  │  ├─settings
 │  │  └─error
 │  ├─mastermind.py
 │  └─requirements.txt
 ├─tests
 ├─README.md
 └─.gitignore
```

---

```plaintext
SOSE-24_SUPERHIRN_14
 ├─src
 │  ├─core
 │  ├─features
 │  │  ├─...
 │  │  ├─tutorial
 │  │  │  ├─tutorial_view.py
 │  │  │  ├─tutorial_viewmodel.py
 │  │  │  └─tutorial_model.py
```

:::::::::::::::::::::::

## Naming-Convention

|                 |                        |
| --------------- | ---------------------- |
| **Classes:**    | `PascalCase`           |
| **Constants:**  | `SCREAMING_SNAKE_CASE` |
| **Functions:**  | `snake_case`           |
| **Attributes:** | `snake_case`           |
|                 |                        |

:::::::::::::::::::::::

## Dateistruktur

```python
import module


class ClassName:
    attribute_name: attribute_type

    def __init__(self):
        self.attribute_name = None

    def method_name(self) -> str:
        ...


if __name__ == "__main__":
    ...
```

:::::::::::::::::::::::

## Type Annotations

#### Classes

```python
class Classname:
    attr_name: attr_type
```

#### Functions

```python
def function(var) -> TYPE
```

**except** for `None`

```python
def function(var)
```

:::::::::::::::::::::::

## Guidelines

#### Black Formatter

<img style="margin: 0; margin-bottom: 30px; position: absolute; top: 0%; left: 80%" src="https://ms-python.gallerycdn.vsassets.io/extensions/ms-python/black-formatter/2024.3.11501016/1716978180354/Microsoft.VisualStudio.Services.Icons.Default" alt="drawing" width="10%">

- Line length:$\phantom{v}$`88`$\phantom{v}$(default)
- Whitespace-Management$\phantom{v}$(`\n\n` $\longrightarrow$ `\n`)
- Trailing commas
- Quoting
  <br>
  ...

:::::::::::::::::::::::

### Quality Assurance

- Unit Test
- Komponententests
- Integrationstests anhand von UseCases
- Code Coverage 100% (Models, ViewModels)

:::::::::::::::::::::::

## Showcase

:::::::::::::::::::::::

## Fragen?

#### Vielen Dank <br>für Ihre Aufmerksamkeit!

<img style="margin: 0; margin-bottom: 30px; position: absolute; top: 0%; left: 60%" src="https://c.tenor.com/p-RObpOP85IAAAAC/tenor.gif" alt="drawing" width="40%">
<!-- <img style="margin: 0; margin-bottom: 30px; position: absolute; top: 0%; left: 60%" src="https://c.tenor.com/6vT_DoPOzq0AAAAd/tenor.gif" alt="drawing" width="40%"> -->

<!-- ::::::::::::::::::::::: -->
