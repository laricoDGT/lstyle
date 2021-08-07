# List of Content

for **responsive** add `sm, md, lg, xl or xxl` with colon `:` before to class name for example:

```bash
<div class="relative md:absolute xl:fixed"></div>
```

## position

```css
.relative {
  position: relative;
}

.absolute {
  position: absolute;
}

.fixed {
  position: fixed;
}

.static {
  position: static;
}

.sticky {
  position: sticky;
}
```

## letter-spacing

letter spacing with base-size: 16px; (_converted "px" to → "rem"_)

**Values** 1, 2, 3, 4, 5, 6;

```css
.ls1 {
  letter-spacing: 0.0625rem;
}

.ls2 {
  letter-spacing: 0.125rem;
}

.ls3 {
  letter-spacing: 0.1875rem;
}

.ls4 {
  letter-spacing: 0.25rem;
}

.ls5 {
  letter-spacing: 0.3125rem;
}

.ls6 {
  letter-spacing: 0.375rem;
}
```

## text-transform

```css
.ttu {
  text-transform: uppercase;
}

.ttl {
  text-transform: lowercase;
}

.ttc {
  text-transform: capitalize;
}
```

## text-decoration

```css
.tdu {
  text-decoration: underline;
}

.tdlt {
  text-decoration: line-through;
}

.tdn {
  text-decoration: none;
}
```

## top right bottom left

```css
.t0 {
  top: 0;
}

.r0 {
  right: 0;
}

.b0 {
  bottom: 0;
}

.l0 {
  left: 0;
}

.t50pct {
  top: 50%;
}

.l50pct {
  left: 50%;
}
```

## line-height

```css
.lh0 {
  line-height: 0;
}

.lh1 {
  line-height: 1;
}

.lh2 {
  line-height: 1.5;
}

.lh3 {
  line-height: 1.8;
}

.lh4 {
  line-height: 2;
}

.lhn {
  line-height: normal;
}
```

## filter

```css
.fi1 {
  filter: invert(1);
}
```

## border-width

border width in pixeles

**Values** 0, 1, 2, 3, 4, 5, 6, 7, 8;

```css
.bw0 {
  border-width: 0px;
}

.bw1 {
  border-width: 1px;
}

.bw3 {
  border-width: 3px;
}

... .bw7 {
  border-width: 7px;
}

.bw8 {
  border-width: 8px;
}
```

## border 0

```css
.bt0 {
  border-top: 0;
}

.br0 {
  border-right: 0;
}

.bb0 {
  border-bottom: 0;
}

.bl0 {
  border-left: 0;
}
```

## border 1

```css
.btw1 {
  border-top-width: 1px;
}

.brw1 {
  border-right-width: 1px;
}

.bbw1 {
  border-bottom-width: 1px;
}

.blw1 {
  border-left-width: 1px;
}
```

## border-style

```css
.bsn {
  border-style: none;
}

.bss {
  border-style: solid;
}

.bsdotted {
  border-style: dotted;
}

.bsdashed {
  border-style: dashed;
}

.bsdouble {
  border-style: double;
}
```

## border-collapse

```css
.bcc {
  border-collapse: collapse;
}

.bcs {
  border-collapse: separate;
}
```

## border-radius

_converted "px" to → "rem"_

**Values** 4 (default), 8, 10, 12

```css
.rounded0 {
  border-radius: 0;
}

.rounded {
  border-radius: 0.25rem;
}

.roundedt {
  border-top-left-radius: 0.25rem;
  border-top-right-radius: 0.25rem;
}

.roundedr {
  border-top-right-radius: 0.25rem;
  border-bottom-right-radius: 0.25rem;
}

.roundedb {
  border-bottom-right-radius: 0.25rem;
  border-bottom-left-radius: 0.25rem;
}

.roundedl {
  border-top-left-radius: 0.25rem;
  border-bottom-left-radius: 0.25rem;
}

.rounded8 {
  border-radius: 0.5rem;
}

.roundedt8 {
  border-top-left-radius: 0.5rem;
  border-top-right-radius: 0.5rem;
}

.roundedr8 {
  border-top-right-radius: 0.5rem;
  border-bottom-right-radius: 0.5rem;
}

.roundedb8 {
  border-bottom-right-radius: 0.5rem;
  border-bottom-left-radius: 0.5rem;
}

.roundedl8 {
  border-top-left-radius: 0.5rem;
  border-bottom-left-radius: 0.5rem;
}

.rounded10 {
  border-radius: 0.625rem;
}

.roundedt10 {
  border-top-left-radius: 0.625rem;
  border-top-right-radius: 0.625rem;
}

.roundedr10 {
  border-top-right-radius: 0.625rem;
  border-bottom-right-radius: 0.625rem;
}

.roundedb10 {
  border-bottom-right-radius: 0.625rem;
  border-bottom-left-radius: 0.625rem;
}

.roundedl10 {
  border-top-left-radius: 0.625rem;
  border-bottom-left-radius: 0.625rem;
}

.rounded12 {
  border-radius: 0.75rem;
}

.roundedt12 {
  border-top-left-radius: 0.75rem;
  border-top-right-radius: 0.75rem;
}

.roundedr12 {
  border-top-right-radius: 0.75rem;
  border-bottom-right-radius: 0.75rem;
}

.roundedb12 {
  border-bottom-right-radius: 0.75rem;
  border-bottom-left-radius: 0.75rem;
}

.roundedl12 {
  border-top-left-radius: 0.75rem;
  border-bottom-left-radius: 0.75rem;
}

.roundedfull {
  border-radius: 9999px;
}

.circle {
  border-radius: 100%;
}
```

## text-align

```css
.tal {
  text-align: left;
}

.tac {
  text-align: center;
}

.tar {
  text-align: right;
}

.taj {
  text-align: justify;
}
```

## text-align-last

```css
.talc {
  text-align-last: center;
}

.talr {
  text-align-last: right;
}
```

## vertical-align

```css
.vabl {
  vertical-align: baseline;
}

.vat {
  vertical-align: top;
}

.vam {
  vertical-align: middle;
}

.vab {
  vertical-align: bottom;
}

.vatt {
  vertical-align: text-top;
}

.vatb {
  vertical-align: text-bottom;
}
```

## white-space

```css
.wsn {
  white-space: normal;
}

.wsnw {
  white-space: nowrap;
}

.wsp {
  white-space: pre;
}

.wspl {
  white-space: pre-line;
}

.wspw {
  white-space: pre-wrap;
}
```

## word-break

```css
.wbn {
  word-break: normal;
  overflow-wrap: normal;
}
.wbba {
  word-break: break-all;
}
.owbw {
  overflow-wrap: break-word;
}
```

## ellipsis

```css
.ellipsis {
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}
```

## opacity

```css
.opacity0 {
  opacity: 0;
}

.opacity10 {
  opacity: 0.1;
}

.opacity20 {
  opacity: 0.2;
}

.opacity30 {
  opacity: 0.3;
}

.opacity40 {
  opacity: 0.4;
}

.opacity50 {
  opacity: 0.5;
}

.opacity60 {
  opacity: 0.6;
}

.opacity70 {
  opacity: 0.7;
}

.opacity80 {
  opacity: 0.8;
}

.opacity90 {
  opacity: 0.9;
}

.opacity100 {
  opacity: 1;
}

.hover\:opacity1:hover {
  opacity: 1;
}
```

## float

```css
.fr {
  float: right;
}

.fl {
  float: left;
}

.fn {
  float: none;
}

.clr:after {
  content: "";
  width: 100%;
  clear: both;
}
```

## visibility

```css
.vv {
  visibility: visible;
}

.vh {
  visibility: hidden;
}
```

## list-style

```css
.lsn {
  list-style: none;
}

.lsd {
  list-style: disc;
}

.lstd {
  list-style-type: decimal;
}
```

## fill

```css
.fc {
  fill: currentColor;
}
```

## stroke

```css
.sc {
  stroke: currentColor;
}
```

## object-fit

```css
.ofcontain {
  object-fit: contain;
}

.ofcover {
  object-fit: cover;
}

.offill {
  object-fit: fill;
}

.ofnone {
  object-fit: none;
}
```

## overflow

```css
.oa {
  overflow: auto;
}

.oh {
  overflow: hidden;
}

.ov {
  overflow: visible;
}

.os {
  overflow: scroll;
}

.oxa {
  overflow-x: auto;
}

.oya {
  overflow-y: auto;
}

.oxh {
  overflow-x: hidden;
}

.oyh {
  overflow-y: hidden;
}

.oxv {
  overflow-x: visible;
}

.oyv {
  overflow-y: visible;
}

.oxs {
  overflow-x: scroll;
}

.oys {
  overflow-y: scroll;
}
```

## z-index

```css
.zi-1 {
  z-index: -1;
}

.zia {
  z-index: auto;
}

.ziover {
  z-index: 9999;
}

.zi-1 {
  z-index: -1;
}

.zi0 {
  z-index: 0;
}

.zi10 {
  z-index: 10;
}

.zi20 {
  z-index: 20;
}

.zi30 {
  z-index: 30;
}

.zi40 {
  z-index: 40;
}

.zi50 {
  z-index: 50;
}
```

## object-position

```css
.opt {
  object-position: top;
}

.opb {
  object-position: bottom;
}

.opl {
  object-position: left;
}

.opr {
  object-position: right;
}

.opc {
  object-position: center;
}

.oplb {
  object-position: left bottom;
}

.oplt {
  object-position: left top;
}

.oprb {
  object-position: right bottom;
}

.oprt {
  object-position: right top;
}
```

## box-shadow

```css
.shadow {
  box-shadow: 0 1px 3px 0 rgba(0, 0, 0, 0.1), 0 1px 2px 0 rgba(0, 0, 0, 0.06);
}

.shadow1 {
  box-shadow: 0 0 0 1px rgba(0, 0, 0, 0.05);
}

.shadow2 {
  box-shadow: 0 1px 2px 0 rgba(0, 0, 0, 0.05);
}

.shadow3 {
  box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
}

.shadow4 {
  box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
}

.shadow5 {
  box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
}

.shadow-none {
  box-shadow: none;
}
```

## overscroll-behavior

```css
.oba {
  overscroll-behavior: auto;
}

.obc {
  overscroll-behavior: contain;
}

.obn {
  overscroll-behavior: none;
}

.obya {
  overscroll-behavior-y: auto;
}

.obyc {
  overscroll-behavior-y: contain;
}

.obyn {
  overscroll-behavior-y: none;
}

.obxa {
  overscroll-behavior-x: auto;
}

.obxc {
  overscroll-behavior-x: contain;
}

.obxn {
  overscroll-behavior-x: none;
}
```

## transition

```css
.tpa {
  transition-property: all;
}

.duration100 {
  transition-duration: 100ms;
}

.detay100 {
  transition-delay: 100ms;
}

.duration200 {
  transition-duration: 200ms;
}

.detay200 {
  transition-delay: 200ms;
}

.duration300 {
  transition-duration: 300ms;
}

.detay300 {
  transition-delay: 300ms;
}

.duration500 {
  transition-duration: 500ms;
}

.detay500 {
  transition-delay: 500ms;
}

.duration600 {
  transition-duration: 600ms;
}

.detay600 {
  transition-delay: 600ms;
}

.duration700 {
  transition-duration: 700ms;
}

.detay700 {
  transition-delay: 700ms;
}
```

## overlay opacity

```css
.overlayopacity2:after {
  content: "";
  display: block;
  width: 100%;
  height: 100%;
  background-color: #000;
  z-index: 1;
  position: absolute;
  left: 0;
  bottom: 0;
  opacity: 0.2;
}

.overlayopacity4:after {
  content: "";
  display: block;
  width: 100%;
  height: 100%;
  background-color: #000;
  z-index: 1;
  position: absolute;
  left: 0;
  bottom: 0;
  opacity: 0.4;
}

.overlayopacity6:after {
  content: "";
  display: block;
  width: 100%;
  height: 100%;
  background-color: #000;
  z-index: 1;
  position: absolute;
  left: 0;
  bottom: 0;
  opacity: 0.6;
}

.overlayopacity8:after {
  content: "";
  display: block;
  width: 100%;
  height: 100%;
  background-color: #000;
  z-index: 1;
  position: absolute;
  left: 0;
  bottom: 0;
  opacity: 0.8;
}
```

## table-layout

```css
.tla {
  table-layout: auto;
}

.tlf {
  table-layout: fixed;
}
```

## appearance

```css
.an {
  appearance: none;
}
```

## outline

```css
.outline0 {
  outline: 0;
}
```

## cursor

```css
.cp {
  cursor: pointer;
}

.cm {
  cursor: move;
}
```

## writing-mode

```css
.wmtbrl {
  writing-mode: tb-rl;
}
```

## container width

```css
.container:not(-full) {
  width: 90%;
  max-width: var(--container-max-width, 1800px);
  margin: auto;
}

.container-full {
  width: 100%;
}
```
