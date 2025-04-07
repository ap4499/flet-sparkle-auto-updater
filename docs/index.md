# Introduction

SparkleAutoUpdater for Flet.

## Examples

```
import flet as ft

from sparkle_auto_updater import SparkleAutoUpdater


def main(page: ft.Page):
    page.vertical_alignment = ft.MainAxisAlignment.CENTER
    page.horizontal_alignment = ft.CrossAxisAlignment.CENTER

    page.add(

                ft.Container(height=150, width=300, alignment = ft.alignment.center, bgcolor=ft.Colors.PURPLE_200, content=SparkleAutoUpdater(
                    tooltip="My new SparkleAutoUpdater Control tooltip",
                    value = "My new SparkleAutoUpdater Flet Control", 
                ),),

    )


ft.app(main)
```

## Classes

[SparkleAutoUpdater](SparkleAutoUpdater.md)


