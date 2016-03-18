# Designkit Forms

## Install

```bash
npm i designkit-forms
```

## Usage

```html
<form action="">
  <label for="">Form Label</label>
  <input class="form-control" type="text" name="name" value="" placeholder="Placeholder text...">
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
  font-size: 12px;
  font-weight: bold;
}

.form-control,
.form-select {
  min-height: 2.125rem;
  padding: 0.4375rem 0.5rem;
  font-size: 13px;
  color: #76899A;
  vertical-align: middle;
  background-color: #fff;
  background-repeat: no-repeat;
  background-position: right 8px center;
  border: 1px solid #D1D6DC;
  border-radius: 2px;
  outline: none;
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.075);
}

.form-control.focus, .form-control:focus,
.form-select.focus,
.form-select:focus {
  border-color: #c3c9d1;
  outline: none;
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.075), 0 0 5px rgba(81, 167, 232, 0.5);
}

.input-sm {
  min-height: 1.625rem;
  padding-top: 0.25rem;
  padding-bottom: 0.25rem;
  font-size: 12px;
}

.input-lg {
  padding: 0.375rem 0.625rem;
  font-size: 16px;
}

.input-block {
  display: block;
  width: 100%;
}
```

## Author

Jason Melgoza

## License

The MIT License (MIT)

Copyright (c) 2016 RightScale

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
