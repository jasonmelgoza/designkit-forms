# Designkit Forms

## Install

```bash
npm i designkit-forms
```

## Usage

```html
<form>
  <label for="name">Basic Form Label</label>
  <input class="form-control" type="text" id="name" placeholder="Placeholder text...">
  <p class="form-note">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
</form>
```

## The CSS

```css
/*
//
// Designkit-Forms
// --------------------------------------------------
*/
fieldset {
  padding: 0;
  margin: 0;
  border: 0;
}

label {
  display: block;
  margin-bottom: .3rem;
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
  color: #bfc8d0;
  vertical-align: middle;
}

.form-control::-moz-placeholder {
  color: #bfc8d0;
  vertical-align: middle;
}

.form-control:-moz-placeholder {
  color: #bfc8d0;
  vertical-align: middle;
}

.form-control:-ms-input-placeholder {
  color: #bfc8d0;
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
}

.form-control.focus, .form-control:focus,
.form-select.focus,
.form-select:focus {
  border-color: #a6afbb;
  border-bottom-color: #a0aab7;
  outline: none;
}

.form-select {
  cursor: pointer;
  border: 1px solid #D1D6DC;
  box-shadow: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  -ms-appearance: none;
  -o-appearance: none;
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

The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
