文件夹 PATH 列表
卷序列号为 2C63-F35B
D:.
│  build.bat
│  directoryList.md
│  Dockerfile
│  LICENSE
│  list.txt
│  Liuliu.Blogs.sln
│  Liuliu.Blogs.sln.DotSettings.user
│  README.md
│  
└─src
    ├─Liuliu.Blogs.Core
    │  │  Liuliu.Blogs.Core.csproj
    │  │  
    │  ├─bin
    │  │  └─Debug
    │  │      │  Liuliu.Blogs.Core.1.0.0.nupkg
    │  │      │  
    │  │      └─netstandard2.0
    │  │              Liuliu.Blogs.Core.deps.json
    │  │              Liuliu.Blogs.Core.dll
    │  │              Liuliu.Blogs.Core.pdb
    │  │              Liuliu.Blogs.Core.xml
    │  │              
    │  ├─Common
    │  │  │  CommonService.cs
    │  │  │  ICommonContract.cs
    │  │  │  
    │  │  └─Dtos
    │  │          ListNode.cs
    │  │          TreeNode.cs
    │  │          
    │  ├─Identity
    │  │  │  IdentityPack.cs
    │  │  │  IdentityService.cs
    │  │  │  IdentityService.UserLogin.cs
    │  │  │  IdentityService.UserRole.cs
    │  │  │  IIdentityContract.cs
    │  │  │  RoleStore.cs
    │  │  │  UserStore.cs
    │  │  │  
    │  │  ├─Dtos
    │  │  │      AutoMapperConfiguration.cs
    │  │  │      ChangePasswordDto.cs
    │  │  │      ConfirmEmailDto.cs
    │  │  │      LoginDto.cs
    │  │  │      ProfileEditDto.cs
    │  │  │      RegisterDto.cs
    │  │  │      ResetPasswordDto.cs
    │  │  │      RoleInputDto.cs
    │  │  │      RoleNode.cs
    │  │  │      RoleOutputDto.cs
    │  │  │      RoleOutputDto2.cs
    │  │  │      SendMailDto.cs
    │  │  │      UserInputDto.cs
    │  │  │      UserLoginOutputDto.cs
    │  │  │      UserOutputDto.cs
    │  │  │      UserOutputDto2.cs
    │  │  │      UserRoleInputDto.cs
    │  │  │      UserRoleNode.cs
    │  │  │      UserRoleOutputDto.cs
    │  │  │      
    │  │  ├─Entities
    │  │  │      LoginLog.cs
    │  │  │      Organization.cs
    │  │  │      Role.cs
    │  │  │      RoleClaim.cs
    │  │  │      User.cs
    │  │  │      UserClaim.cs
    │  │  │      UserDetail.cs
    │  │  │      UserLogin.cs
    │  │  │      UserRole.cs
    │  │  │      UserToken.cs
    │  │  │      
    │  │  └─Events
    │  │          LoginEventData.cs
    │  │          Login_LoginLogEventHandler.cs
    │  │          LogoutEventData.cs
    │  │          Logout_LoginLogEventHandler.cs
    │  │          RegisterEventData.cs
    │  │          
    │  ├─obj
    │  │  │  Liuliu.Blogs.Core.csproj.nuget.cache
    │  │  │  Liuliu.Blogs.Core.csproj.nuget.dgspec.json
    │  │  │  Liuliu.Blogs.Core.csproj.nuget.g.props
    │  │  │  Liuliu.Blogs.Core.csproj.nuget.g.targets
    │  │  │  project.assets.json
    │  │  │  
    │  │  └─Debug
    │  │      │  Liuliu.Blogs.Core.1.0.0.nuspec
    │  │      │  
    │  │      └─netstandard2.0
    │  │              Liuliu.Blogs.Core.AssemblyInfo.cs
    │  │              Liuliu.Blogs.Core.AssemblyInfoInputs.cache
    │  │              Liuliu.Blogs.Core.assets.cache
    │  │              Liuliu.Blogs.Core.csproj.CoreCompileInputs.cache
    │  │              Liuliu.Blogs.Core.csproj.FileListAbsolute.txt
    │  │              Liuliu.Blogs.Core.csprojAssemblyReference.cache
    │  │              Liuliu.Blogs.Core.dll
    │  │              Liuliu.Blogs.Core.pdb
    │  │              
    │  ├─Security
    │  │  │  DataAuthCache.cs
    │  │  │  FunctionAuthCache.cs
    │  │  │  ModuleHandler.cs
    │  │  │  SecurityManager.cs
    │  │  │  SecurityPack.cs
    │  │  │  
    │  │  ├─Dtos
    │  │  │      AutoMapperConfiguration.cs
    │  │  │      EntityInfoNode.cs
    │  │  │      EntityInfoOutputDto.cs
    │  │  │      EntityRoleInputDto.cs
    │  │  │      EntityRoleOutputDto.cs
    │  │  │      FunctionOutputDto.cs
    │  │  │      FunctionOutputDto2.cs
    │  │  │      ModuleInputDto.cs
    │  │  │      ModuleOutputDto.cs
    │  │  │      ModuleSetFunctionDto.cs
    │  │  │      RoleSetModuleDto.cs
    │  │  │      UserSetModuleDto.cs
    │  │  │      UserSetRoleDto.cs
    │  │  │      
    │  │  └─Entities
    │  │          EntityRole.cs
    │  │          EntityUser.cs
    │  │          Module.cs
    │  │          ModuleFunction.cs
    │  │          ModuleRole.cs
    │  │          ModuleUser.cs
    │  │          
    │  └─Systems
    │      │  AuditDatabaseStore.cs
    │      │  AuditPack.cs
    │      │  AuditService.cs
    │      │  IAuditContract.cs
    │      │  ISystemsContract.cs
    │      │  SystemsService.cs
    │      │  
    │      ├─Dtos
    │      │      AuditEntityOutputDto.cs
    │      │      AuditOperationOutputDto.cs
    │      │      AuditPropertyOutputDto.cs
    │      │      GenerateCodeInputDto.cs
    │      │      PackOutputDto.cs
    │      │      SystemSetting.cs
    │      │      
    │      └─Entities
    │              AuditEntity.cs
    │              AuditOperation.cs
    │              AuditProperty.cs
    │              
    ├─Liuliu.Blogs.EntityConfiguration
    │  │  Liuliu.Blogs.EntityConfiguration.csproj
    │  │  
    │  ├─bin
    │  │  └─Debug
    │  │      └─netstandard2.0
    │  │              Liuliu.Blogs.Core.dll
    │  │              Liuliu.Blogs.Core.pdb
    │  │              Liuliu.Blogs.Core.xml
    │  │              Liuliu.Blogs.EntityConfiguration.deps.json
    │  │              Liuliu.Blogs.EntityConfiguration.dll
    │  │              Liuliu.Blogs.EntityConfiguration.pdb
    │  │              Liuliu.Blogs.EntityConfiguration.xml
    │  │              
    │  ├─Identity
    │  │      LoginLogConfiguration.cs
    │  │      OrganizationConfiguration.cs
    │  │      RoleClaimConfiguration.cs
    │  │      RoleConfiguration.cs
    │  │      UserClaimConfiguration.cs
    │  │      UserConfiguration.cs
    │  │      UserDetailConfiguration.cs
    │  │      UserLoginConfiguration.cs
    │  │      UserRoleConfiguration.cs
    │  │      UserTokenConfiguration.cs
    │  │      
    │  ├─obj
    │  │  │  Liuliu.Blogs.EntityConfiguration.csproj.nuget.cache
    │  │  │  Liuliu.Blogs.EntityConfiguration.csproj.nuget.dgspec.json
    │  │  │  Liuliu.Blogs.EntityConfiguration.csproj.nuget.g.props
    │  │  │  Liuliu.Blogs.EntityConfiguration.csproj.nuget.g.targets
    │  │  │  project.assets.json
    │  │  │  
    │  │  └─Debug
    │  │      └─netstandard2.0
    │  │              Liuliu.Blogs.EntityConfiguration.AssemblyInfo.cs
    │  │              Liuliu.Blogs.EntityConfiguration.AssemblyInfoInputs.cache
    │  │              Liuliu.Blogs.EntityConfiguration.assets.cache
    │  │              Liuliu.Blogs.EntityConfiguration.csproj.CopyComplete
    │  │              Liuliu.Blogs.EntityConfiguration.csproj.CoreCompileInputs.cache
    │  │              Liuliu.Blogs.EntityConfiguration.csproj.FileListAbsolute.txt
    │  │              Liuliu.Blogs.EntityConfiguration.csprojAssemblyReference.cache
    │  │              Liuliu.Blogs.EntityConfiguration.dll
    │  │              Liuliu.Blogs.EntityConfiguration.pdb
    │  │              
    │  ├─Security
    │  │      EntityRoleConfiguration.cs
    │  │      EntityUserConfiguration.cs
    │  │      ModuleConfiguration.cs
    │  │      ModuleFunctionConfiguration.cs
    │  │      ModuleRoleConfiguration.cs
    │  │      ModuleUserConfiguration.cs
    │  │      
    │  └─Systems
    │          AuditEntityConfiguration.cs
    │          AuditOperationConfiguration.cs
    │          AuditPropertyConfiguration.cs
    │          KeyValueConfiguration.cs
    │          
    ├─Liuliu.Blogs.Web
    │  │  appsettings.Development.json
    │  │  appsettings.json
    │  │  Dockerfile
    │  │  Liuliu.Blogs.Web.csproj
    │  │  log4net.config
    │  │  Program.cs
    │  │  Startup.cs
    │  │  
    │  ├─Areas
    │  │  └─Admin
    │  │      └─Controllers
    │  │          │  AdminApiController.cs
    │  │          │  DashboardController.cs
    │  │          │  HomeController.cs
    │  │          │  
    │  │          ├─Identity
    │  │          │      RoleController.cs
    │  │          │      UserController.cs
    │  │          │      UserRoleController.cs
    │  │          │      
    │  │          ├─Security
    │  │          │      EntityInfoController.cs
    │  │          │      FunctionController.cs
    │  │          │      ModuleController.cs
    │  │          │      RoleEntityController.cs
    │  │          │      RoleFunctionController.cs
    │  │          │      UserFunctionController.cs
    │  │          │      
    │  │          └─Systems
    │  │                  AuditEntityController.cs
    │  │                  AuditOperationController.cs
    │  │                  PackController.cs
    │  │                  SettingsController.cs
    │  │                  
    │  ├─bin
    │  │  └─Debug
    │  │      ├─netcoreapp2.1
    │  │      │      Liuliu.Blogs.Web.xml
    │  │      │      
    │  │      └─netcoreapp2.2
    │  │              Liuliu.Blogs.Core.dll
    │  │              Liuliu.Blogs.Core.pdb
    │  │              Liuliu.Blogs.Core.xml
    │  │              Liuliu.Blogs.EntityConfiguration.dll
    │  │              Liuliu.Blogs.EntityConfiguration.pdb
    │  │              Liuliu.Blogs.EntityConfiguration.xml
    │  │              Liuliu.Blogs.Web.deps.json
    │  │              Liuliu.Blogs.Web.dll
    │  │              Liuliu.Blogs.Web.pdb
    │  │              Liuliu.Blogs.Web.runtimeconfig.dev.json
    │  │              Liuliu.Blogs.Web.runtimeconfig.json
    │  │              Liuliu.Blogs.Web.xml
    │  │              log4net.config
    │  │              
    │  ├─Controllers
    │  │      CommonController.cs
    │  │      IdentityController.cs
    │  │      SecurityController.cs
    │  │      Test2Controller.cs
    │  │      TestController.cs
    │  │      
    │  ├─Hangfire
    │  │      HangfireJobRunner.cs
    │  │      
    │  ├─log
    │  │  └─2019-05-03
    │  │          Debug.log
    │  │          Error.log
    │  │          Info.log
    │  │          Warn.log
    │  │          
    │  ├─Migrations
    │  │      20190430130752_Init.cs
    │  │      20190430130752_Init.Designer.cs
    │  │      DefaultDbContextModelSnapshot.cs
    │  │      
    │  ├─obj
    │  │  │  Liuliu.Blogs.Web.csproj.nuget.cache
    │  │  │  Liuliu.Blogs.Web.csproj.nuget.dgspec.json
    │  │  │  Liuliu.Blogs.Web.csproj.nuget.g.props
    │  │  │  Liuliu.Blogs.Web.csproj.nuget.g.targets
    │  │  │  project.assets.json
    │  │  │  
    │  │  └─Debug
    │  │      └─netcoreapp2.2
    │  │              Liuliu.Blogs.Web.AssemblyInfo.cs
    │  │              Liuliu.Blogs.Web.AssemblyInfoInputs.cache
    │  │              Liuliu.Blogs.Web.assets.cache
    │  │              Liuliu.Blogs.Web.csproj.CopyComplete
    │  │              Liuliu.Blogs.Web.csproj.CoreCompileInputs.cache
    │  │              Liuliu.Blogs.Web.csproj.FileListAbsolute.txt
    │  │              Liuliu.Blogs.Web.csprojAssemblyReference.cache
    │  │              Liuliu.Blogs.Web.dll
    │  │              Liuliu.Blogs.Web.pdb
    │  │              Liuliu.Blogs.Web.RazorAssemblyInfo.cache
    │  │              Liuliu.Blogs.Web.RazorAssemblyInfo.cs
    │  │              Liuliu.Blogs.Web.RazorTargetAssemblyInfo.cache
    │  │              
    │  ├─Properties
    │  │  │  launchSettings.json
    │  │  │  
    │  │  └─PublishProfiles
    │  │          FolderProfile.pubxml
    │  │          
    │  └─Startups
    │          AspNetCoreMvcPack.cs
    │          CodeGeneratorPack.cs
    │          MySqlDefaultDbContextMigrationPack.cs
    │          MySqlDesignTimeDefaultDbContextFactory.cs
    │          OracleDefaultDbContextMigrationPack.cs
    │          OracleDesignTimeDefaultDbContextFactory.cs
    │          PostgreSqlDefaultDbContextMigrationPack.cs
    │          PostgreSqlDesignTimeDefaultDbContextFactory.cs
    │          SignalrPack.cs
    │          SqliteDefaultDbContextMigrationPack.cs
    │          SqliteDesignTimeDefaultDbContextFactory.cs
    │          SqlServerDefaultDbContextMigrationPack.cs
    │          SqlServerDesignTimeDefaultDbContextFactory.cs
    │          
    └─ui
        └─ng-alain
            │  .editorconfig
            │  .gitignore
            │  .prettierignore
            │  .prettierrc
            │  .stylelintrc
            │  angular.json
            │  LICENSE
            │  package-lock.json
            │  package.json
            │  proxy.config.json
            │  README-zh_CN.md
            │  README.md
            │  tsconfig.json
            │  tslint.json
            │  
            ├─e2e
            │  │  protractor.conf.js
            │  │  tsconfig.e2e.json
            │  │  
            │  └─src
            │          app.e2e-spec.ts
            │          app.po.ts
            │          
            ├─scripts
            │      color-less.js
            │      ng.cmd
            │      
            ├─src
            │  │  ant-svg-icons.ts
            │  │  browserslist
            │  │  favicon.ico
            │  │  hmr.ts
            │  │  index.html
            │  │  karma.conf.js
            │  │  kendo.shim.d.ts
            │  │  main.ts
            │  │  polyfills.ts
            │  │  style-icons-auto.ts
            │  │  style-icons.ts
            │  │  styles.less
            │  │  test.ts
            │  │  tsconfig.app.json
            │  │  tsconfig.spec.json
            │  │  tslint.json
            │  │  typings.d.ts
            │  │  
            │  ├─app
            │  │  │  app.component.ts
            │  │  │  app.module.ts
            │  │  │  delon.module.ts
            │  │  │  
            │  │  ├─core
            │  │  │  │  core.module.ts
            │  │  │  │  index.ts
            │  │  │  │  module-import-guard.ts
            │  │  │  │  README.md
            │  │  │  │  
            │  │  │  ├─i18n
            │  │  │  │      i18n.service.spec.ts
            │  │  │  │      i18n.service.ts
            │  │  │  │      
            │  │  │  ├─net
            │  │  │  │      default.interceptor.ts
            │  │  │  │      
            │  │  │  └─startup
            │  │  │          startup.service.ts
            │  │  │          
            │  │  ├─layout
            │  │  │  │  layout.module.ts
            │  │  │  │  
            │  │  │  ├─default
            │  │  │  │  │  default.component.html
            │  │  │  │  │  default.component.less
            │  │  │  │  │  default.component.ts
            │  │  │  │  │  
            │  │  │  │  ├─header
            │  │  │  │  │  │  header.component.html
            │  │  │  │  │  │  header.component.ts
            │  │  │  │  │  │  index.md
            │  │  │  │  │  │  
            │  │  │  │  │  └─components
            │  │  │  │  │          fullscreen.component.ts
            │  │  │  │  │          i18n.component.ts
            │  │  │  │  │          icon.component.ts
            │  │  │  │  │          notify.component.ts
            │  │  │  │  │          search.component.ts
            │  │  │  │  │          storage.component.ts
            │  │  │  │  │          task.component.ts
            │  │  │  │  │          user.component.ts
            │  │  │  │  │          
            │  │  │  │  ├─setting-drawer
            │  │  │  │  │      setting-drawer-item.component.html
            │  │  │  │  │      setting-drawer-item.component.ts
            │  │  │  │  │      setting-drawer.component.html
            │  │  │  │  │      setting-drawer.component.ts
            │  │  │  │  │      
            │  │  │  │  └─sidebar
            │  │  │  │          sidebar.component.html
            │  │  │  │          sidebar.component.ts
            │  │  │  │          
            │  │  │  ├─fullscreen
            │  │  │  │      fullscreen.component.html
            │  │  │  │      fullscreen.component.ts
            │  │  │  │      
            │  │  │  └─passport
            │  │  │          passport.component.html
            │  │  │          passport.component.less
            │  │  │          passport.component.ts
            │  │  │          
            │  │  ├─routes
            │  │  │  │  routes.module.ts
            │  │  │  │  routes.routing.ts
            │  │  │  │  
            │  │  │  ├─callback
            │  │  │  │      callback.component.ts
            │  │  │  │      
            │  │  │  ├─dashboard
            │  │  │  │      dashboard.component.html
            │  │  │  │      dashboard.component.less
            │  │  │  │      dashboard.component.ts
            │  │  │  │      
            │  │  │  ├─exception
            │  │  │  │      403.component.ts
            │  │  │  │      404.component.ts
            │  │  │  │      500.component.ts
            │  │  │  │      exception-routing.module.ts
            │  │  │  │      exception.module.ts
            │  │  │  │      trigger.component.ts
            │  │  │  │      
            │  │  │  ├─identity
            │  │  │  │  │  identity.module.ts
            │  │  │  │  │  identity.routing.ts
            │  │  │  │  │  
            │  │  │  │  ├─role
            │  │  │  │  │      role.component.html
            │  │  │  │  │      role.component.ts
            │  │  │  │  │      
            │  │  │  │  ├─user
            │  │  │  │  │      user.component.html
            │  │  │  │  │      user.component.ts
            │  │  │  │  │      
            │  │  │  │  └─user-role
            │  │  │  │          user-role.component.html
            │  │  │  │          user-role.component.ts
            │  │  │  │          
            │  │  │  ├─passport
            │  │  │  │  │  passport.module.ts
            │  │  │  │  │  passport.routing.ts
            │  │  │  │  │  
            │  │  │  │  ├─email
            │  │  │  │  │      confirm-email.component.ts
            │  │  │  │  │      send-confirm-mail.component.ts
            │  │  │  │  │      
            │  │  │  │  ├─lock
            │  │  │  │  │      lock.component.html
            │  │  │  │  │      lock.component.less
            │  │  │  │  │      lock.component.ts
            │  │  │  │  │      
            │  │  │  │  ├─login
            │  │  │  │  │      login.component.html
            │  │  │  │  │      login.component.less
            │  │  │  │  │      login.component.ts
            │  │  │  │  │      
            │  │  │  │  ├─oauth-callback
            │  │  │  │  │      oauth-callback.component.html
            │  │  │  │  │      oauth-callback.component.ts
            │  │  │  │  │      
            │  │  │  │  ├─password
            │  │  │  │  │      forgot-password.component.ts
            │  │  │  │  │      reset-password.component.html
            │  │  │  │  │      reset-password.component.ts
            │  │  │  │  │      
            │  │  │  │  ├─register
            │  │  │  │  │      register.component.html
            │  │  │  │  │      register.component.ts
            │  │  │  │  │      
            │  │  │  │  ├─register-result
            │  │  │  │  │      register-result.component.html
            │  │  │  │  │      register-result.component.ts
            │  │  │  │  │      
            │  │  │  │  └─shared
            │  │  │  │      └─send-mail
            │  │  │  │              send-mail.component.html
            │  │  │  │              send-mail.component.ts
            │  │  │  │              
            │  │  │  ├─profile
            │  │  │  │  │  profile.component.html
            │  │  │  │  │  profile.component.less
            │  │  │  │  │  profile.component.ts
            │  │  │  │  │  profile.module.ts
            │  │  │  │  │  profile.routing.ts
            │  │  │  │  │  
            │  │  │  │  ├─edit
            │  │  │  │  │      edit.component.html
            │  │  │  │  │      edit.component.ts
            │  │  │  │  │      
            │  │  │  │  ├─oauth2
            │  │  │  │  │      oauth2.component.html
            │  │  │  │  │      oauth2.component.ts
            │  │  │  │  │      
            │  │  │  │  ├─password
            │  │  │  │  │      password.component.html
            │  │  │  │  │      password.component.ts
            │  │  │  │  │      
            │  │  │  │  └─settings
            │  │  │  │          settings.component.html
            │  │  │  │          settings.component.ts
            │  │  │  │          
            │  │  │  ├─security
            │  │  │  │  │  security.module.ts
            │  │  │  │  │  security.routing.ts
            │  │  │  │  │  
            │  │  │  │  ├─entityinfo
            │  │  │  │  │      entityinfo.component.html
            │  │  │  │  │      entityinfo.component.ts
            │  │  │  │  │      
            │  │  │  │  ├─function
            │  │  │  │  │      function.component.html
            │  │  │  │  │      function.component.ts
            │  │  │  │  │      
            │  │  │  │  ├─module
            │  │  │  │  │      module.component.html
            │  │  │  │  │      module.component.ts
            │  │  │  │  │      
            │  │  │  │  ├─role-entityinfo
            │  │  │  │  │      role-entityinfo.component.html
            │  │  │  │  │      role-entityinfo.component.ts
            │  │  │  │  │      
            │  │  │  │  ├─role-function
            │  │  │  │  │      role-function.component.html
            │  │  │  │  │      role-function.component.ts
            │  │  │  │  │      
            │  │  │  │  └─user-function
            │  │  │  │          user-function.component.html
            │  │  │  │          user-function.component.ts
            │  │  │  │          
            │  │  │  └─systems
            │  │  │      │  systems.module.ts
            │  │  │      │  systems.routing.ts
            │  │  │      │  
            │  │  │      ├─audit-entity
            │  │  │      │      audit-entity.component.html
            │  │  │      │      audit-entity.component.ts
            │  │  │      │      
            │  │  │      ├─audit-operation
            │  │  │      │      audit-operation.component.html
            │  │  │      │      audit-operation.component.ts
            │  │  │      │      
            │  │  │      ├─data-dictionary
            │  │  │      │      data-dictionary.component.html
            │  │  │      │      data-dictionary.component.ts
            │  │  │      │      
            │  │  │      ├─pack
            │  │  │      │      pack.component.html
            │  │  │      │      pack.component.ts
            │  │  │      │      
            │  │  │      └─settings
            │  │  │              settings.component.html
            │  │  │              settings.component.ts
            │  │  │              
            │  │  └─shared
            │  │      │  index.ts
            │  │      │  shared.module.ts
            │  │      │  
            │  │      ├─components
            │  │      │  ├─ad-search
            │  │      │  │  │  ad-search.component.html
            │  │      │  │  │  ad-search.component.ts
            │  │      │  │  │  
            │  │      │  │  └─modal
            │  │      │  │          modal.component.html
            │  │      │  │          modal.component.ts
            │  │      │  │          
            │  │      │  ├─filter-group
            │  │      │  │      filter-group.component.html
            │  │      │  │      filter-group.component.ts
            │  │      │  │      filter-rule.component.html
            │  │      │  │      filter-rule.component.ts
            │  │      │  │      
            │  │      │  └─modal-tree
            │  │      │          modal-tree.component.ts
            │  │      │          
            │  │      ├─json-schema
            │  │      │      json-schema.module.ts
            │  │      │      
            │  │      ├─osharp
            │  │      │  │  osharp.model.ts
            │  │      │  │  osharp.module.ts
            │  │      │  │  
            │  │      │  ├─cache
            │  │      │  │      cache.module.ts
            │  │      │  │      cache.service.ts
            │  │      │  │      local-store-cache.service.ts
            │  │      │  │      memory-cache.service.ts
            │  │      │  │      
            │  │      │  ├─components
            │  │      │  │      kendoui-combobox.component.ts
            │  │      │  │      kendoui-function.component.ts
            │  │      │  │      kendoui-splitter.component.ts
            │  │      │  │      kendoui-tabstrip.component.ts
            │  │      │  │      kendoui-treeview.component.ts
            │  │      │  │      kendoui-window.component.ts
            │  │      │  │      st-component-base.ts
            │  │      │  │      
            │  │      │  ├─directives
            │  │      │  │      remote-inverse-validator.directive.ts
            │  │      │  │      remote-validator.directive.ts
            │  │      │  │      
            │  │      │  └─services
            │  │      │          identity.service.ts
            │  │      │          kendoui.service.ts
            │  │      │          ng-alain.service.ts
            │  │      │          ng-alain.types.ts
            │  │      │          osharp.service.ts
            │  │      │          
            │  │      └─utils
            │  │              yuan.ts
            │  │              
            │  ├─assets
            │  │  │  .gitkeep
            │  │  │  alain-default.less
            │  │  │  logo-color.svg
            │  │  │  logo-full.svg
            │  │  │  logo.svg
            │  │  │  zorro.svg
            │  │  │  
            │  │  ├─osharp
            │  │  │  │  app-data.json
            │  │  │  │  logo-color.svg
            │  │  │  │  logo-full.svg
            │  │  │  │  logo.svg
            │  │  │  │  
            │  │  │  └─i18n
            │  │  │          en-US.json
            │  │  │          zh-CN.json
            │  │  │          zh-TW.json
            │  │  │          
            │  │  └─res
            │  │          github.svg
            │  │          sprite.png
            │  │          
            │  ├─environments
            │  │      environment.hmr.ts
            │  │      environment.prod.ts
            │  │      environment.ts
            │  │      
            │  └─styles
            │          index.less
            │          theme.less
            │          
            ├─_cli-tpl
            │  └─test
            │      └─__path__
            │          └─__name@dasherize@if-flat__
            │                  __name@dasherize__.component.html
            │                  __name@dasherize__.component.spec.ts
            │                  __name@dasherize__.component.ts
            │                  
            └─_mock
                    index.ts
                    README.md
                    _user.ts
                    
