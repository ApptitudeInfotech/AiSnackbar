# AiSnackbar
Minimal Snackbar / Notification React Component

![npm bundle size](https://img.shields.io/bundlephobia/min/@aiui/ai-snackbar)
![npm bundle size](https://img.shields.io/bundlephobia/minzip/@aiui/ai-snackbar)
![npm download](https://img.shields.io/npm/dm/@aiui/ai-snackbar.svg)

## Install
    npm i @aiui/ai-snackbar

## Import
    import AiSnackbar from '@aiui/ai-snackbar';


## Props
|   Name          |  Type  |   Default    | Description |
|-----------------|:-------|:-------------|:------------|
| opened          | bool   | false        | If true, the snackbar is open |
| message         | string |              | Snackbar Message |
| onClose         | func   | ( ) => { }   | Callback fired when the component requests to be closed|
| kind            | string |  default     | Snackbar Kind ('default', 'info', 'error', 'success', 'warning') |