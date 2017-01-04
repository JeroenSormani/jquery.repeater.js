# Repeater.js
This is used in Reviewer extensions. Not per-se usable for other purposes


Example usage
```
jQuery( '.reviewer-tables-wrap' ).repeater({
    addTrigger: '.reviewer-table-row-add',
    removeTrigger: '.reviewer-table-row-remove',
    template: '.reviewer-collapsible-template .reviewer-table-row',
    elementWrap: '.reviewer-table-row',
    elementsContainer: '.reviewer-tables',
});
```
