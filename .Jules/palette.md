## 2024-10-24 - Required Form Fields Lack Visual and Structural Cues
**Learning:** In this application, form fields relying on the HTML5 `required` attribute lack explicit visual indicators (like an asterisk) and structural cues for screen readers, making them difficult to identify for both sighted and non-sighted users.
**Action:** When adding or fixing required fields, always append `<span class="text-error" aria-hidden="true">*</span>` to the label and add `aria-required="true"` to the input element to ensure consistent accessibility and UX.
