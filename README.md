# Obsidian Widgets

Adds cool widgets within Obsidian notes

## Usage

To insert a widget, simply add a code block with the language `widgets` and add your options to the body

````
```widgets
<OPTIONS>
```
````

Currently, the available widgets are:

## Clock

![Clock](public/clock.png)

#### Configuration Body

`type`: clock

`format`: the time format you want to display on the clock. Supports "12hr", "24hr"

#### Example

````
```widgets
type: clock
format: "12hr" | "24hr"
```
````

## Quote

![Quote](public/quote.png)

#### Configuration Body:

`type`: quote

`quote`: the quote you want to display

`author`: the author of the quote (optional)

#### Example

````
```widgets
type: quote
quote: Lorem ipsum dolor sit amet
author: Lorem Ipsum
```
````

## Countdown

![Countdown](public/countdown.png)

#### Configuration Body:

`type`: countdown

`date`: Must be in the format `YYYY-MM-DD HH:MM:SS`

`to`: Description of the countdown (optional)

#### Example

````
```widgets
type: countdown
date: 2024-01-01 00:00:00
to: New Year! 🎉
```
````

## Customizing your widgets

We currently do not support and don't plan to support customizing styles and colors of each widget via options in the widgets code block. Each widget is set to respect your theme's colors. That does not mean you can further customize the look of your widgets to your liking via CSS Snippets.

If you want to customize your widgets, please follow the [guide in our wiki](https://github.com/rafaelveiga/obsidian-widgets/wiki/Customizing-your-widgets-colors-styles)

## Command Pallete

Obsidian Widgets also comes with a handy command on the command pallete (Ctrl+P) to add widgets on the fly

![Command Pallete](public/command-pallete.png)

## Suggestions

-   [Widget requests, bugs, new feature requests](https://github.com/rafaelveiga/obsidian-widgets/issues)

## Support

If you find this plugin useful and would like to support its development, you can sponsor me on Ko-Fi

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Z8Z0SNIS3)
