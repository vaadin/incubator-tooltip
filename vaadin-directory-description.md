[![Available in Vaadin_Directory](https://img.shields.io/vaadin-directory/v/vaadinvaadin-tooltip.svg)](https://vaadin.com/directory/component/vaadinvaadin-tooltip)
[![Stars in Vaadin_Directory](https://img.shields.io/vaadin-directory/stars/vaadinvaadin-tooltip.svg)](https://vaadin.com/directory/component/vaadinvaadin-tooltip)

# &lt;vaadin-tooltip&gt;

[&lt;vaadin-tooltip&gt;](https://vaadin.com/components/vaadin-tooltip) is a Web Component providing an easy way to ask the user to confirm a choice, part of the [Vaadin components](https://vaadin.com/components).

[<img src="https://raw.githubusercontent.com/vaadin/vaadin-tooltip/master/screenshot.png" width="200" alt="Screenshot of vaadin-tooltip">](https://vaadin.com/components/vaadin-tooltip)

## Example Usage

```html
  <vaadin-tooltip header="Unsaved changes" confirm-text="Save" on-confirm="save"
    cancel on-cancel="cancel" reject reject-text="Discard" on-reject="discard">
    Do you want to save or discard your changes before navigating away?
  </vaadin-tooltip>
```
