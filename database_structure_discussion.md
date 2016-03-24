Bulunmasi gereken tablo ve fieldleri ekleyip/duzenleyip/cikarabilirsiniz.


User
  - username
  - email
  - gender
  - birthday
  - password
  - created_at  
  - updated_at
  - deleted_at
  - last_login_date
  - avatar

Title -> "Topic" olarak değişmeli
  - name
  - slug
  - is_hidden (??)
  - created_at
  - updated_at (denormalized suggestion for sorting)
  - entry_count (denormalized suggestion for fast read queries in table)
  - deleted_at
  - redirect_to
  - User (?)

Entry
  - User
  - Title -> "Topic" olarak değişmeli
  - content
  - created_at
  - updated_at
  - deleted_at
  
Role
  - name
  - permissions
  
Role_To_User (ismi sallıyorum kendini anlatsın diye)
  - User
  - Role
