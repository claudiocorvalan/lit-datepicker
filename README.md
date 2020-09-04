
`crca-lit-datepicker` fork lit-datepicker provides a simple datepicker with range.

### Install

    npm install crca-lit-datepicker

Fork @doubletrade/lit-datepicker Inspired by [airbnb datepicker](https://github.com/airbnb/react-dates).

```js
  // Simple
  return html`<lit-datepicker .dateFrom=${dateFrom} .dateTo=${dateTo}></lit-datepicker>`;

  // No range
  return html`<lit-datepicker noRange></lit-datepicker>`;

  // No range and narrow view
  return html`<lit-datepicker noRange forceNarrow></lit-datepicker>`;

  // i18n
  return html`<lit-datepicker locale="es"></lit-datepicker>`;

  // Inputs
  const input = (dateFrom, dateTo) => html`
    <paper-input .value="${dateFrom} - ${dateTo}" readonly label="Input">
      <paper-icon-button slot="suffix" icon="today"></paper-icon-button>
    </paper-input>`;
  return html`<lit-datepicker-input .html="${input}" dateFormat="dd/MM/yyyy" locale="en"></lit-datepicker-input>`;
```
