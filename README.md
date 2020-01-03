# ng8-pagination
Pagination is implemented with the &lt;jw-pagination> component that comes with the jw-angular-pagination package available on npm.

# Styling the Pagination Component
The JW Angular pagination component is unstyled by default, you can use the below CSS selectors to add your own custom styles.

You can also plug in Bootstrap (3.x or 4.x) which the component works well with, that's what I used in the example.

.pagination - Pagination component container (ul element)

.pagination .page-item - All list items in the pagination component

.pagination .page-item .page-link - All pagination links including first, last, previous and next

.pagination .number-item - All page numbers (1, 2, 3 etc) pagination elements

.pagination .first-item - The 'First' pagination element

.pagination .last-item - The 'Last' pagination element

.pagination .previous-item - The 'Previous' pagination element

.pagination .next-item - The 'Next' pagination element

# Hiding Pagination Buttons
To hide any of the buttons you can simply set them to display: none; using the css selectors described above.

# Ref
https://jasonwatmore.com/post/2019/06/18/angular-8-simple-pagination-example
