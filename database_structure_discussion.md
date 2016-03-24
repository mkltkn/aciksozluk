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

Title
  - name
  - slug
  - is_hidden (?)
  - created_at
  - updated_at (denormalized suggestion for sorting)
  - entry_count (denormalized suggestion for fast read queries in table)
  - deleted_at
  - User (?)


Entry
  - User
  - Title
  - content
  - created_at
  - updated_at
  - deleted_at
  
