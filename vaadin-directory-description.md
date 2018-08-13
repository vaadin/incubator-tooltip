[![Available in Vaadin_Directory](https://img.shields.io/vaadin-directory/v/vaadinincubator-tooltip.svg)](https://vaadin.com/directory/component/vaadinincubator-tooltip)
[![Stars in Vaadin_Directory](https://img.shields.io/vaadin-directory/stars/vaadinincubator-tooltip.svg)](https://vaadin.com/directory/component/vaadinincubator-tooltip)

# &lt;incubator-tooltip&gt;

[&lt;incubator-tooltip&gt;](https://vaadin.com/components/incubator-tooltip) is a Web Component providing an easy way to ask the user to confirm a choice, part of the [Vaadin components](https://vaadin.com/components).

[<img src="https://raw.githubusercontent.com/vaadin/incubator-tooltip/master/screenshot.png" width="200" alt="Screenshot of incubator-tooltip">](https://vaadin.com/components/incubator-tooltip)

## Example Usage

```html
  <incubator-tooltip header="Unsaved changes" confirm-text="Save" on-confirm="save"
    cancel on-cancel="cancel" reject reject-text="Discard" on-reject="discard">
    Do you want to save or discard your changes before navigating away?
  </incubator-tooltip>
```
