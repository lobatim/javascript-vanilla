Este é um projeto de aprendizagem de um tutorial oficial do angularJS disponível em:
https://docs.angularjs.org/tutorial
<!doctype html>
<html lang="en" ng-app="phonecatApp">
  <head>
    <meta charset="utf-8">
    <title>phone shop</title>
    <link rel="stylesheet" href="app/lib/bootstrap/dist/css/bootstrap.css" />
    <link rel="stylesheet" href="app/app.animations.css" />
    <link rel="stylesheet" href="app/app.css" />
    <script src="app/lib/angular/angular.js"></script>
    <script src="app/lib/jquery/dist/jquery.js"></script>
    <script src="app/lib/angular-animate/angular-animate.js"></script>
    <script src="app/app.animations.js"></script>
    <script src="app/lib/angular-route/angular-route.js"></script>
    <script src="app/app.module.js"></script>
    <script src="app/app.config.js"></script>
    <script src="app/core/core.module.js"></script>
    <script src="app/core/checkmark/checkmark.filter.js"></script>
    <script src="app/phone-list/phone-list.module.js"></script>
    <script src="app/phone-list/phone-list.component.js"></script>
    <script src="app/phone-detail/phone-detail.module.js"></script>
    <script src="app/phone-detail/phone-detail.component.js"></script>
    <script src="app/lib/angular-resource/angular-resource.js"></script>
    <script src="app/core/phone/phone.module.js"></script>
    <script src="app/core/phone/phone.service.js"></script>
  </head>
  <body>
    <div class="view-container">
      <div ng-view class="view-frame"></div>
    </div>

  </body>
</html>
