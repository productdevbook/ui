# productdevbook/ui

Headless components for React, Vue, Svelte, Angular and Solid. Write it once, run it five ways.

[![One component set. Five frameworks.](https://ui.productdevbook.com/og.png)](https://ui.productdevbook.com)

**[Website](https://ui.productdevbook.com)** · **[Docs](https://ui.productdevbook.com/docs)** · **[Compare](https://ui.productdevbook.com/compare)** · **[Help name it](https://ui.productdevbook.com/names)** · **[Early access](https://ui.productdevbook.com/apply)**

> [!WARNING]
> This is work in progress, still research. I'm building it in public. You can follow along on X [@productdevbook](https://x.com/productdevbook) and on the [website](https://ui.productdevbook.com).

## Why

Focus. Keyboard. ARIA. State. The parts that take months, written **once**, below the framework. Above it, a thin layer that speaks React, Vue, Svelte, Angular and Solid. No styles. Your rules.

## How it works

Three layers. One behavior.

| Layer | What it holds |
| --- | --- |
| `core` | State and logic. No framework, no DOM. |
| `dom` | Focus, keyboard, pointer, positioning, ARIA. No framework. |
| adapters | Components, props and events in your framework: React, Vue, Svelte, Angular, Solid. |

Every adapter runs the same upstream behavior tests, and a parity harness drives the same scenarios with real input in Chromium, Firefox and WebKit and compares the DOM, the events and the focus of all five frameworks. On the [Compare](https://ui.productdevbook.com/compare) page, pick any component and try it in all five frameworks side by side; [open one dialog](https://ui.productdevbook.com/compare?component=dialog) and the other four follow.

## Roadmap

On the website now, 60 components in all five frameworks:

- [x] Accordion
- [x] Alert Dialog
- [x] Autocomplete
- [x] Avatar
- [x] Button
- [x] Calendar
- [x] Carousel
- [x] Checkbox
- [x] Checkbox Group
- [x] Collapsible
- [x] Color Picker
- [x] Color Swatch
- [x] Color Swatch Picker
- [x] Combobox
- [x] Context Menu
- [x] Data Table
- [x] Date Field
- [x] Date Picker
- [x] Date Range Picker
- [x] Date Time Field
- [x] Dialog
- [x] Drawer
- [x] Field
- [x] File Upload
- [x] Filterable Menu
- [x] Form
- [x] Grid List
- [x] Input
- [x] Listbox
- [x] Menu
- [x] Menubar
- [x] Meter
- [x] Navigation Menu
- [x] Number Field
- [x] OTP Field
- [x] Pagination
- [x] Popover
- [x] Preview Card
- [x] Progress
- [x] Radio
- [x] Radio Group
- [x] Range Calendar
- [x] Rating
- [x] Rating Display
- [x] Scroll Area
- [x] Select
- [x] Separator
- [x] Slider
- [x] Splitter
- [x] Stepper
- [x] Switch
- [x] Tabs
- [x] Time Field
- [x] Toast
- [x] Toggle
- [x] Toggle Group
- [x] Toolbar
- [x] Tooltip
- [x] Tree
- [x] Tree Select
- [x] Server rendering and hydration in React, Vue, Svelte, Angular and Solid

Coming:

- [ ] Fieldset
- [ ] A name

The full list of components still to come is in [#4](https://github.com/productdevbook/ui/issues/4).

## It does not have a name yet

The package scope is `@▢▢▢▢` for now. [Suggest one, vote for the ones you like](https://ui.productdevbook.com/names). The shortlist is decided in public.

## Early access

No account, no sign-in. [Leave your email](https://ui.productdevbook.com/apply), the frameworks you use and, if you like, your GitHub username.

## Credits

The behavior is ported from [Base UI](https://github.com/mui/base-ui) by the MUI team, and its test suite is what every adapter is checked against. This project is not affiliated with MUI.

## License

MIT
