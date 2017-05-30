# Repeater.js
This is used in Reviewer extensions. Not per-se usable for other purposes


Example usage
```
jQuery( document ).ready( function() {
    jQuery( '.repeater-wrap' ).repeater({
        addTrigger: '.repeater-add-row',
        removeTrigger: '.repeater-remove-row',
        template: '.repeater-template .repeater-row',
        elementWrap: '.repeater-row',
        elementsContainer: '.repeater-rows',
    });
});
```

Example HTML
```
<div class="repeater-wrap">
    <div class="repeater-rows">

        <div class="repeater-row">test</div>
        <div class="repeater-row">test</div>
        <div class="repeater-row">test</div>

    </div>

    <div class="repeater-template" style="display: none;">
        <div class="repeater-row">New</div>
    </div>
    <a href="javascript:void(0);" class="repeater-add-row">Add new</a>

</div>
```
