Co możesz zrobić żeby włączyć projekt? 
  1.  W pliku appsettings.json zmienić connection string na własny serwer. 
      czyli zmienić fragment miedzy "*..*" 
      "DefaultConnection": "*Server=ITP0166\\SQLEXPRESS*;Database=aspnet-UserManagement.MVC-AE2969B3-75AD-4EA0-A236-44AF57519291;Trusted_Connection=True;MultipleActiveResultSets=true"
  
  2.  Zaaktualizować baze danych za pomocą Package Manager Console
      PM > update-database –verbose
      
  3. Właczyć projekt -> Login -> 
                                Email/Login : superadmin 
                                Hasło: 123Pa$$word.

What can you do to enable the project? 
  1. In the appsettings.json file change the connection string to your own server. 
      That means change the connection string between "*..*" 
      "DefaultConnection": "Server=*ITP0166SQLEXPRESS*;Database=aspnet-UserManagement.MVC-AE2969B3-75AD-4EA0-A236-              44AF57519291;Trusted_Connection=True;MultipleActiveResultSets=true"
  
  2. Update database using Package Manager Console
      PM > update-database -verbose
      
  3. Start the project -> Login -> 
                                Email/Login : superadmin 
                                Password: 123Pa$$word.
