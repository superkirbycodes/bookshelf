
Bookshelf

- [ ] # books_controller.rb, change the previous line to:
@books = Books.paginate :page => params[:page], :per_page => 10

- [ ] # index.html.erb, add this line after the loop:
<%= will_paginate @books %>
- [Reference](https://github.com/ahawkins/Nettuts-Zero-to-Sixty/blob/master/config/environments/test.rb)
+ Error
 - Head back to your /makes page
 - When page being refreshed routes error pertaining '/makes'
