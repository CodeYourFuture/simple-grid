# simple-grid

- Always wrap your entire page with a `container`.
- Wrap each set of elements in a `row`
- Don't change the width, padding-left, padding-right, margin-left or margin-right of the items that have a `[size]-col-[x]` class on them. 

Example usage:

```      
      <section class="block-of-items row">

        <div class="item-wrapper xs-col-12 md-col-6 lg-col-3">
          <div class="item">
            <!-- content goes here -->
          </div>
        </div>

        <div class="item-wrapper xs-col-12 md-col-6 lg-col-3">
          <div class="item">
            <!-- content goes here -->
          </div>
        </div>

        <div class="item-wrapper xs-col-12 md-col-6 lg-col-3">
          <div class="item">
            <!-- content goes here -->
          </div>
        </div>

        <div class="item-wrapper xs-col-12 md-col-6 lg-col-3">
          <div class="item">
            <!-- content goes here -->
          </div>
        </div>

      </section>
```