# route
Componente Route do Framework Zyne

resources :users
# generates:
#   get "/users" -- index on your controller
#   get "/users/:id" -- show on your controller
#   get "/users/new" -- new method on your controller
#   post "/users" -- create on your controller
#   get "/users/:id/edit" -- edit method on your controller
#   put "/users/:id" -- update on your controller
#   patch "/users/:id" -- update on your controller
#   delete "/users/:id" -- destroy on your controller