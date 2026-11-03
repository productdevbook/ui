# productdevbook/ui

Headless components for React, Vue, Svelte and Angular. Write it once, run it four ways.

[![One component set. Four frameworks.](https://ui.productdevbook.com/og.png)](https://ui.productdevbook.com)

**[Website](https://ui.productdevbook.com)** · **[Docs](https://ui.productdevbook.com/docs)** · **[Compare](https://ui.productdevbook.com/compare)** · **[Help name it](https://ui.productdevbook.com/names)** · **[Early access](https://ui.productdevbook.com/apply)**

> [!WARNING]
> This is work in progress, still research. I'm building it in public. You can follow along on X [@productdevbook](https://x.com/productdevbook) and on the [website](https://ui.productdevbook.com).

## Why

Focus. Keyboard. ARIA. State. The parts that take months, written **once**, below the framework. Above it, a thin layer that speaks React, Vue, Svelte and Angular. No styles. Your rules.

## How it works

Three layers. One behavior.

| Layer | What it holds |
| --- | --- |
| `core` | State and logic. No framework, no DOM. |
| `dom` | Focus, keyboard, pointer, positioning, ARIA. No framework. |
| adapters | Components, props and events in your framework: React, Vue, Svelte, Angular. |

Every adapter runs the same upstream behavior tests, and a parity harness drives the same scenarios with real input in Chromium, Firefox and WebKit and compares the DOM, the events and the focus of all four frameworks. On the [Compare](https://ui.productdevbook.com/compare) page, open one dialog and the other three follow.

## Roadmap

On the website now:

- [x] Switch
- [x] Field
- [x] Form
- [x] Dialog
- [x] Alert Dialog
- [x] Menu
- [x] Filterable Menu
- [x] Context Menu
- [x] Menubar
- [x] Popover
- [x] Tooltip
- [x] Separator
- [x] Button
- [x] Input
- [x] Toggle
- [x] Avatar
- [x] Progress
- [x] Meter
- [x] Collapsible

Coming:

- [ ] Accordion
- [ ] Autocomplete
- [ ] Checkbox
- [ ] Checkbox Group
- [ ] Combobox
- [ ] Drawer
- [ ] Fieldset
- [ ] Navigation Menu
- [ ] Number Field
- [ ] OTP Field
- [ ] Preview Card
- [ ] Radio
- [ ] Radio Group
- [ ] Scroll Area
- [ ] Select
- [ ] Slider
- [ ] Tabs
- [ ] Toast
- [ ] Toggle Group
- [ ] Toolbar
- [ ] Server rendering and hydration in every framework
- [ ] A name

## It does not have a name yet

The package scope is `@▢▢▢▢` for now. [Suggest one, vote for the ones you like](https://ui.productdevbook.com/names). The shortlist is decided in public.

## Early access

No account, no sign-in. [Leave your email](https://ui.productdevbook.com/apply), the frameworks you use and, if you like, your GitHub username.

## Credits

The behavior is ported from [Base UI](https://github.com/mui/base-ui) by the MUI team, and its test suite is what every adapter is checked against. This project is not affiliated with MUI.

## License

MIT
