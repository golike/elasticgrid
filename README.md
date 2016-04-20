# elasticgrid
A more flexible alternative to CSS float-based grids

We stopped using tables for page layout because they aren't semantically correct, and because they added extra markup to our html. But float-based grids make it harder to get flexible layouts with columns that expand to fill space. Tables, while they have their annoying quirks, do give that flexibility. Elasticgrids make use of table rendering, while allowing you to keep the same lighter-weight markup of the row and column float-based grid approach of Bootstrap and other frameworks.

## Usage
An elasticgrid uses two main elements: rows and columns.

    <div class="row">
        <div class="col">column 1</div>
        <div class="col">column 2</div>
    </div>
