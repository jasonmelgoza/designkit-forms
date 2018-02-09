# designkit-forms
1.2.0

Sass module for css forms at RightScale.

## Install
```
npm i --save designkit-forms
```

### CSS

```css
fieldset {
  padding: 0;
  margin: 0;
  border: 0;
}

label {
  display: block;
  margin-bottom: 5px;
  font-size: 11px;
  font-weight: bold;
  color: #57626C;
}

.form-note {
  min-height: 17px;
  margin: 4px 0 2px;
  font-size: 12px;
  color: #76899A;
}

.form-control::-webkit-input-placeholder {
  color: #8d9dab;
  vertical-align: middle;
}

.form-control:-ms-input-placeholder {
  color: #8d9dab;
  vertical-align: middle;
}

.form-control::placeholder {
  color: #8d9dab;
  vertical-align: middle;
}

.form-control,
.form-select {
  min-height: 36px;
  padding: 8px;
  font-size: 13px;
  color: #76899A;
  vertical-align: middle;
  background-color: #fff;
  border: 1px solid #D1D6DC;
  border-top-color: #cbd1d8;
  border-radius: 2px;
  outline: none;
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.08);
  transition: border-color ease-in-out .15s,box-shadow ease-in-out .15s;
}

.form-control.focus, .form-control:focus,
.form-select.focus,
.form-select:focus {
  border-color: #97a2b0;
  border-bottom-color: #919dac;
  outline: none;
  box-shadow: none;
}

.form-control[disabled],
.form-control .disabled,
.form-select[disabled],
.form-select .disabled {
  color: #90a0ad;
  background: #F4F5F7;
  border-color: #D1D6DC;
  box-shadow: none;
}

.form-select {
  display: inline-block;
  max-width: 100%;
  padding-right: 24px;
  cursor: pointer;
  background: #fff url("data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz48c3ZnIHdpZHRoPSI5cHgiIGhlaWdodD0iNnB4IiB2aWV3Qm94PSIwIDAgOSA2IiB2ZXJzaW9uPSIxLjEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiPiAgICAgICAgPHRpdGxlPkdyb3VwQDJ4PC90aXRsZT4gICAgPGRlc2M+Q3JlYXRlZCB3aXRoIFNrZXRjaC48L2Rlc2M+ICAgIDxkZWZzPjwvZGVmcz4gICAgPGcgaWQ9IlBhZ2UtMSIgc3Ryb2tlPSJub25lIiBzdHJva2Utd2lkdGg9IjEiIGZpbGw9Im5vbmUiIGZpbGwtcnVsZT0iZXZlbm9kZCI+ICAgICAgICA8ZyBpZD0iR3JvdXAiIGZpbGwtcnVsZT0ibm9uemVybyIgZmlsbD0iIzg1OTZBNSI+ICAgICAgICAgICAgPGcgaWQ9ImNhcmV0Ij4gICAgICAgICAgICAgICAgPHBhdGggZD0iTTksMC4yIEM4LjksMC4xIDguOCwwIDguNywwIEwwLjMsMCBDMC4yLDAgMC4xLDAuMSAwLDAuMiBMMCwwLjMgTDAuMSwwLjYgTDQuMyw1LjkgTDQuNSw2IEw0LjcsNS45IEw4LjksMC42IEw5LDAuNCBMOSwwLjIgWiIgaWQ9IlNoYXBlIj48L3BhdGg+ICAgICAgICAgICAgPC9nPiAgICAgICAgPC9nPiAgICA8L2c+PC9zdmc+") no-repeat right 8px center;
  border: 1px solid #D1D6DC;
  box-shadow: none;
  -webkit-appearance: none;
     -moz-appearance: none;
          appearance: none;
}

.input-sm {
  min-height: 26px;
  padding-top: 4px;
  padding-bottom: 4px;
  font-size: 12px;
}

.input-lg {
  padding: 10px;
  font-size: 16px;
}

.input-block {
  display: block;
  width: 100%;
}

.form-checkbox {
  padding-left: 20px;
  margin: 15px 0;
  vertical-align: middle;
}

.form-checkbox label {
  margin-bottom: 0;
  font-size: 12px;
  line-height: 1.8;
}

.form-checkbox input[type=checkbox],
.form-checkbox input[type=radio] {
  float: left;
  margin: 5px 0 0 -20px;
  vertical-align: middle;
}

.form-checkbox .form-note {
  display: block;
  margin: 0;
  font-size: 12px;
  font-weight: normal;
}

```

## Author

Jason Melgoza

## License

MIT
