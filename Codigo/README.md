
```
Codigo
├─ .env
├─ client
│  ├─ .dockerignore
│  ├─ Dockerfile
│  ├─ eslint.config.js
│  ├─ index.html
│  ├─ package-lock.json
│  ├─ package.json
│  ├─ public
│  │  └─ vite.svg
│  ├─ README.md
│  ├─ src
│  │  ├─ App.jsx
│  │  ├─ assets
│  │  │  ├─ adaclogoredonda.png
│  │  │  ├─ dog.png
│  │  │  ├─ fotocadastro.png
│  │  │  ├─ fotocadastroPet.png
│  │  │  ├─ LandingPage
│  │  │  │  ├─ adotar.png
│  │  │  │  ├─ contato.png
│  │  │  │  ├─ facebook.png
│  │  │  │  ├─ instagram.png
│  │  │  │  ├─ local.png
│  │  │  │  ├─ main-dog.png
│  │  │  │  ├─ voluntario.png
│  │  │  │  └─ wpp.png
│  │  │  ├─ login-image.png
│  │  │  ├─ pqvolunt.png
│  │  │  └─ react.svg
│  │  ├─ components
│  │  │  ├─ BarChartExample.jsx
│  │  │  ├─ ButtonComponent.jsx
│  │  │  ├─ CalendarComponent.jsx
│  │  │  ├─ CalendarPicker.jsx
│  │  │  ├─ CardTarefas.jsx
│  │  │  ├─ ColumnTarefas.jsx
│  │  │  ├─ EventModal.jsx
│  │  │  ├─ FeedbackSection.jsx
│  │  │  ├─ Header.jsx
│  │  │  ├─ LineChartExample.jsx
│  │  │  ├─ ListEventModal.jsx
│  │  │  ├─ Menu.jsx
│  │  │  ├─ Modal.jsx
│  │  │  ├─ Modals
│  │  │  │  ├─ AddPatrocinioModal.jsx
│  │  │  │  ├─ AddTarefaModal.jsx
│  │  │  │  ├─ DeleteTarefaModal.jsx
│  │  │  │  └─ UpdateTarefaModal.jsx
│  │  │  ├─ ModalUpdateTarefa.jsx
│  │  │  ├─ PatrocinioSection.jsx
│  │  │  ├─ PieChartExample.jsx
│  │  │  ├─ PrivateRoute.jsx
│  │  │  ├─ SearchComponent.jsx
│  │  │  └─ VolunteerComponent.jsx
│  │  ├─ main.jsx
│  │  ├─ pages
│  │  │  ├─ AnalisarFeedback.jsx
│  │  │  ├─ Cadastro.jsx
│  │  │  ├─ CadastroPet.jsx
│  │  │  ├─ CadastroVoluntario.jsx
│  │  │  ├─ Calendar.jsx
│  │  │  ├─ Dashboard.jsx
│  │  │  ├─ Formulario.jsx
│  │  │  ├─ HistoricoAdocao.jsx
│  │  │  ├─ LandingPage.jsx
│  │  │  ├─ Layout.jsx
│  │  │  ├─ Login.jsx
│  │  │  ├─ NovoFeedback.jsx
│  │  │  ├─ Patrocinio.jsx
│  │  │  ├─ Perfil.jsx
│  │  │  ├─ PetPefil.jsx
│  │  │  ├─ Pets.jsx
│  │  │  ├─ RecoverPassword.jsx
│  │  │  ├─ RecuperarSenha.jsx
│  │  │  ├─ ResetPassword.jsx
│  │  │  ├─ Tarefas.jsx
│  │  │  └─ Voluntarios.jsx
│  │  ├─ routes
│  │  │  └─ AppRoutes.jsx
│  │  ├─ services
│  │  │  ├─ AuthService.jsx
│  │  │  ├─ EventoService.jsx
│  │  │  ├─ TarefaService.jsx
│  │  │  └─ UserService.jsx
│  │  └─ styles
│  │     ├─ App.css
│  │     ├─ Cadastro.css
│  │     ├─ CadastroPet.css
│  │     ├─ CadastroVoluntario.css
│  │     ├─ CalendarComponent.css
│  │     ├─ Dashboard.css
│  │     ├─ FeedbackList.css
│  │     ├─ FeedbackSection.css
│  │     ├─ Formulario.css
│  │     ├─ Header.css
│  │     ├─ index.css
│  │     ├─ LandingPage.css
│  │     ├─ Layout.css
│  │     ├─ ListEventModal.css
│  │     ├─ Login.css
│  │     ├─ Modal.css
│  │     ├─ Patrocinio.css
│  │     ├─ Perfil.css
│  │     ├─ PerfilPet.css
│  │     ├─ Pets.css
│  │     ├─ RecuperarSenha.css
│  │     ├─ Tarefas.css
│  │     └─ Voluntarios.css
│  └─ vite.config.js
├─ database
│  ├─ Dockerfile
│  └─ init.sql
├─ docker-compose.yml
└─ server
   ├─ .dockerignore
   ├─ .env
   ├─ app.js
   ├─ babel.config.cjs
   ├─ Dockerfile
   ├─ jest.config.js
   ├─ package-lock.json
   ├─ package.json
   ├─ prisma
   │  ├─ migrations
   │  │  ├─ 20241202185856_
   │  │  │  └─ migration.sql
   │  │  ├─ 20241203231111_
   │  │  │  └─ migration.sql
   │  │  └─ migration_lock.toml
   │  └─ schema.prisma
   ├─ README.md
   ├─ server.js
   ├─ src
   │  ├─ config
   │  │  └─ upload.js
   │  ├─ controllers
   │  │  ├─ AdocaoController.js
   │  │  ├─ AuthController.js
   │  │  ├─ EventoController.js
   │  │  ├─ FeedbackController.js
   │  │  ├─ PatrocinioController.js
   │  │  ├─ PetController.js
   │  │  ├─ TarefaController.js
   │  │  ├─ TarefaUsuarioController.js
   │  │  └─ UsuarioController.js
   │  ├─ database
   │  │  └─ prismaClient.js
   │  ├─ routes
   │  │  ├─ adocaoRoutes.js
   │  │  ├─ authRoutes.js
   │  │  ├─ eventosRoutes.js
   │  │  ├─ feedbackRoutes.js
   │  │  ├─ patrocinioRoutes.js
   │  │  ├─ petsRoutes.js
   │  │  ├─ routes.js
   │  │  ├─ tarefaRoutes.js
   │  │  └─ usuarioRoutes.js
   │  ├─ services
   │  │  ├─ AdocaoService.js
   │  │  ├─ AuthService.js
   │  │  ├─ EmailService.js
   │  │  ├─ EventoService.js
   │  │  ├─ FeedbackService.js
   │  │  ├─ PatrocinioService.js
   │  │  ├─ PetService.js
   │  │  ├─ TarefaService.js
   │  │  ├─ TarefaUsuarioService.js
   │  │  └─ UsuarioService.js
   │  └─ util
   │     └─ Util.js
   ├─ test
   │  └─ controllers
   │     ├─ AdocaoController.test.js
   │     ├─ AuthController.test.js
   │     ├─ EventoController.test.js
   │     └─ FeedbackController.test.js
   ├─ uploads
   │  ├─ img-1729030301118-414125445.png
   │  ├─ img-1729030426214-573060491.png
   │  ├─ img-1729030546273-568132806.png
   │  ├─ img-1729030931429-817098230.png
   │  ├─ img-1729031153654-828597292.png
   │  ├─ img-1729031162837-1680631.png
   │  ├─ img-1729031175193-949803133.png
   │  ├─ img-1729031328521-334519660.png
   │  ├─ img-1729031346651-445323203.png
   │  ├─ img-1729031600090-411781710.png
   │  ├─ img-1729031639219-472573795.png
   │  ├─ img-1729031750302-836418626.png
   │  ├─ img-1729031823309-187288940.png
   │  ├─ img-1729031906233-406957217.png
   │  ├─ img-1729032108714-577976564.png
   │  ├─ img-1729032133975-790041231.png
   │  ├─ img-1729032333339-541145403.png
   │  ├─ img-1729032393524-54074729.png
   │  ├─ img-1729032735371-686933179.png
   │  ├─ img-1729032962970-515684861.png
   │  ├─ img-1729033052553-879680894.png
   │  ├─ img-1729033198425-634625373.png
   │  ├─ img-1729033368419-333743940.png
   │  ├─ img-1729035225992-424144817.png
   │  ├─ img-1729035335371-167321691.png
   │  ├─ img-1729035834099-406112091.png
   │  ├─ img-1729035956707-75960724.png
   │  ├─ img-1729039355029-46985499.png
   │  ├─ img-1729102944365-310759766.png
   │  ├─ img-1729105976572-907408781.png
   │  ├─ img-1729128568245-371675379.png
   │  ├─ img-1729135110760-67931029.png
   │  ├─ img-1729175899377-316038242.png
   │  ├─ img-1729175927250-91111372.png
   │  ├─ img-1729175952932-35774268.png
   │  ├─ img-1729175957439-546340774.png
   │  ├─ img-1729176666328-986303865.png
   │  ├─ img-1729177091491-244802032.png
   │  ├─ img-1729189285580-490652674.png
   │  ├─ img-1729219678181-573588236.png
   │  ├─ img-1729220986353-167897325.png
   │  ├─ img-1729222610018-224692047.png
   │  ├─ img-1729536306658-11771237.png
   │  ├─ img-1729538486181-234164027.png
   │  ├─ img-1729538716146-102140204.png
   │  ├─ img-1729538847676-614437668.png
   │  ├─ img-1729539353629-376013863.png
   │  ├─ img-1729539456632-892468226.png
   │  ├─ img-1729539632936-54340188.png
   │  ├─ img-1729539861261-228401433.png
   │  ├─ img-1729543337950-604535672.png
   │  ├─ img-1729544013531-549985485.png
   │  ├─ img-1729544040755-620142643.png
   │  ├─ img-1729545436723-11625655.png
   │  ├─ img-1729545508194-152145950.png
   │  ├─ img-1729545529803-534913859.png
   │  ├─ img-1729545583096-541903263.png
   │  ├─ img-1729551999074-328682056.jpg
   │  ├─ img-1732279430197-263254943.jpg
   │  ├─ img-1732280616292-650671594.png
   │  ├─ img-1733170724872-323167719.png
   │  ├─ img-1733170743311-644078559.png
   │  ├─ img-1733171079687-112619712.jpg
   │  ├─ img-1733171124580-79295906.jpg
   │  ├─ img-1733171166172-824727501.jpg
   │  ├─ img-1733171314153-267844077.jpg
   │  ├─ img-1733171743437-131411399.jpg
   │  ├─ img-1733171845492-979132119.jpg
   │  ├─ img-1733171937755-153435302.jpg
   │  ├─ img-1733172294345-644546655.jpg
   │  ├─ img-1733173798763-315338363.jpg
   │  ├─ img-1733173804495-690726313.jpg
   │  ├─ img-1733173813589-187028147.jpg
   │  ├─ img-1733176224689-475094664.jpg
   │  └─ img-1733232414465-619975478.jpg
   └─ wait-for-it.sh

```