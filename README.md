# googlem

<!DOCTYPE html>
<html lang="en">
  <head>
  <script>(function(){function e(a){this.t={};this.tick=function(a,c,b){var d=void 0!=b?b:(new Date).getTime();this.t[a]=[d,c];if(void 0==b)try{window.console.timeStamp("CSI/"+a)}catch(e){}};this.tick("start",null,a)}var a;window.performance&&(a=window.performance.timing);var f=a?new e(a.responseStart):new e;window.jstiming={Timer:e,load:f};if(a){var c=a.navigationStart,d=a.responseStart;0<c&&d>=c&&(window.jstiming.srt=d-c)}if(a){var b=window.jstiming.load;0<c&&d>=c&&(b.tick("_wtsrt",void 0,c),b.tick("wtsrt_",
"_wtsrt",d),b.tick("tbsd_","wtsrt_"))}try{a=null,window.chrome&&window.chrome.csi&&(a=Math.floor(window.chrome.csi().pageT),b&&0<c&&(b.tick("_tbnd",void 0,window.chrome.csi().startE),b.tick("tbnd_","_tbnd",c))),null==a&&window.gtbExternal&&(a=window.gtbExternal.pageT()),null==a&&window.external&&(a=window.external.pageT,b&&0<c&&(b.tick("_tbnd",void 0,window.external.startE),b.tick("tbnd_","_tbnd",c))),a&&(window.jstiming.pt=a)}catch(g){}})();
</script>
  <script>
  window.jstiming.load.name = 'SignIn';
  </script>
  <meta charset="utf-8">
  <meta content="width=300, initial-scale=1" name="viewport">
  <title>Sign in - Google Accounts</title>
<style>html, body {
  font-family: Arial, sans-serif;
  background: #fff;
  margin: 0;
  padding: 0;
  border: 0;
  position: absolute;
  height: 100%;
  min-width: 100%;
  font-size: 13px;
  color: #404040;
  direction: ltr;
  -webkit-text-size-adjust: none;
  }
  button,
  input[type=button],
  input[type=submit] {
  font-family: Arial, sans-serif;
  font-size: 13px;
  }
  a,
  a:hover,
  a:visited {
  color: #427fed;
  cursor: pointer;
  text-decoration: none;
  }
  a:hover {
  text-decoration: underline;
  }
  h1 {
  font-size: 20px;
  color: #262626;
  margin: 0 0 15px;
  font-weight: normal;
  }
  h2 {
  font-size: 14px;
  color: #262626;
  margin: 0 0 15px;
  font-weight: bold;
  }
  input[type=email],
  input[type=number],
  input[type=password],
  input[type=tel],
  input[type=text],
  input[type=url] {
  -moz-appearance: none;
  -webkit-appearance: none;
  appearance: none;
  display: inline-block;
  height: 36px;
  padding: 0 8px;
  margin: 0;
  background: #fff;
  border: 1px solid #d9d9d9;
  border-top: 1px solid #c0c0c0;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  -moz-border-radius: 1px;
  -webkit-border-radius: 1px;
  border-radius: 1px;
  font-size: 15px;
  color: #404040;
  }
  input[type=email]:hover,
  input[type=number]:hover,
  input[type=password]:hover,
  input[type=tel]:hover,
  input[type=text]:hover,
  input[type=url]:hover {
  border: 1px solid #b9b9b9;
  border-top: 1px solid #a0a0a0;
  -moz-box-shadow: inset 0 1px 2px rgba(0,0,0,0.1);
  -webkit-box-shadow: inset 0 1px 2px rgba(0,0,0,0.1);
  box-shadow: inset 0 1px 2px rgba(0,0,0,0.1);
  }
  input[type=email]:focus,
  input[type=number]:focus,
  input[type=password]:focus,
  input[type=tel]:focus,
  input[type=text]:focus,
  input[type=url]:focus {
  outline: none;
  border: 1px solid #4d90fe;
  -moz-box-shadow: inset 0 1px 2px rgba(0,0,0,0.3);
  -webkit-box-shadow: inset 0 1px 2px rgba(0,0,0,0.3);
  box-shadow: inset 0 1px 2px rgba(0,0,0,0.3);
  }
  input[type=checkbox],
  input[type=radio] {
  -webkit-appearance: none;
  display: inline-block;
  width: 13px;
  height: 13px;
  margin: 0;
  cursor: pointer;
  vertical-align: bottom;
  background: #fff;
  border: 1px solid #c6c6c6;
  -moz-border-radius: 1px;
  -webkit-border-radius: 1px;
  border-radius: 1px;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  position: relative;
  }
  input[type=checkbox]:active,
  input[type=radio]:active {
  background: #ebebeb;
  }
  input[type=checkbox]:hover {
  border-color: #c6c6c6;
  -moz-box-shadow: inset 0 1px 2px rgba(0,0,0,0.1);
  -webkit-box-shadow: inset 0 1px 2px rgba(0,0,0,0.1);
  box-shadow: inset 0 1px 2px rgba(0,0,0,0.1);
  }
  input[type=radio] {
  -moz-border-radius: 1em;
  -webkit-border-radius: 1em;
  border-radius: 1em;
  width: 15px;
  height: 15px;
  }
  input[type=checkbox]:checked,
  input[type=radio]:checked {
  background: #fff;
  }
  input[type=radio]:checked::after {
  content: '';
  display: block;
  position: relative;
  top: 3px;
  left: 3px;
  width: 7px;
  height: 7px;
  background: #666;
  -moz-border-radius: 1em;
  -webkit-border-radius: 1em;
  border-radius: 1em;
  }
  input[type=checkbox]:checked::after {
  content: url("https://ssl.gstatic.com/ui/v1/menu/checkmark.png");
  display: block;
  position: absolute;
  top: -6px;
  left: -5px;
  }
  input[type=checkbox]:focus {
  outline: none;
  border-color: #4d90fe;
  }
  .stacked-label {
  display: block;
  font-weight: bold;
  margin: .5em 0;
  }
  .hidden-label {
  position: absolute !important;
  clip: rect(1px 1px 1px 1px); /* IE6, IE7 */
  clip: rect(1px, 1px, 1px, 1px);
  height: 0px;
  width: 0px;
  overflow: hidden;
  visibility: hidden;
  }
  input[type=checkbox].form-error,
  input[type=email].form-error,
  input[type=number].form-error,
  input[type=password].form-error,
  input[type=text].form-error,
  input[type=tel].form-error,
  input[type=url].form-error {
  border: 1px solid #dd4b39;
  }
  .error-msg {
  margin: .5em 0;
  display: block;
  color: #dd4b39;
  line-height: 17px;
  }
  .help-link {
  background: #dd4b39;
  padding: 0 5px;
  color: #fff;
  font-weight: bold;
  display: inline-block;
  -moz-border-radius: 1em;
  -webkit-border-radius: 1em;
  border-radius: 1em;
  text-decoration: none;
  position: relative;
  top: 0px;
  }
  .help-link:visited {
  color: #fff;
  }
  .help-link:hover {
  color: #fff;
  background: #c03523;
  text-decoration: none;
  }
  .help-link:active {
  opacity: 1;
  background: #ae2817;
  }
  .wrapper {
  position: relative;
  min-height: 100%;
  }
  .content {
  padding: 0 44px;
  }
  .main {
  padding-bottom: 100px;
  }
  /* For modern browsers */
  .clearfix:before,
  .clearfix:after {
  content: "";
  display: table;
  }
  .clearfix:after {
  clear: both;
  }
  /* For IE 6/7 (trigger hasLayout) */
  .clearfix {
  zoom:1;
  }
  .google-header-bar {
  height: 71px;
  border-bottom: 1px solid #e5e5e5;
  overflow: hidden;
  }
  .header .logo {
  margin: 17px 0 0;
  float: left;
  height: 38px;
  width: 116px;
  }
  .header .secondary-link {
  margin: 28px 0 0;
  float: right;
  }
  .header .secondary-link a {
  font-weight: normal;
  }
  .google-header-bar.centered {
  border: 0;
  height: 108px;
  }
  .google-header-bar.centered .header .logo {
  float: none;
  margin: 40px auto 30px;
  display: block;
  }
  .google-header-bar.centered .header .secondary-link {
  display: none
  }
  .google-footer-bar {
  position: absolute;
  bottom: 0;
  height: 35px;
  width: 100%;
  border-top: 1px solid #e5e5e5;
  overflow: hidden;
  }
  .footer {
  padding-top: 7px;
  font-size: .85em;
  white-space: nowrap;
  line-height: 0;
  }
  .footer ul {
  float: left;
  max-width: 80%;
  padding: 0;
  }
  .footer ul li {
  color: #737373;
  display: inline;
  padding: 0;
  padding-right: 1.5em;
  }
  .footer a {
  color: #737373;
  }
  .lang-chooser-wrap {
  float: right;
  display: inline;
  }
  .lang-chooser-wrap img {
  vertical-align: top;
  }
  .lang-chooser {
  font-size: 13px;
  height: 24px;
  line-height: 24px;
  }
  .lang-chooser option {
  font-size: 13px;
  line-height: 24px;
  }
  .hidden {
  height: 0px;
  width: 0px;
  overflow: hidden;
  visibility: hidden;
  display: none !important;
  }
  .banner {
  text-align: center;
  }
  .card {
  background-color: #f7f7f7;
  padding: 20px 25px 30px;
  margin: 0 auto 25px;
  width: 304px;
  -moz-border-radius: 2px;
  -webkit-border-radius: 2px;
  border-radius: 2px;
  -moz-box-shadow: 0px 2px 2px rgba(0, 0, 0, 0.3);
  -webkit-box-shadow: 0px 2px 2px rgba(0, 0, 0, 0.3);
  box-shadow: 0px 2px 2px rgba(0, 0, 0, 0.3);
  }
  .card > *:first-child {
  margin-top: 0;
  }
  .rc-button,
  .rc-button:visited {
  display: inline-block;
  min-width: 46px;
  text-align: center;
  color: #444;
  font-size: 14px;
  font-weight: 700;
  height: 36px;
  padding: 0 8px;
  line-height: 36px;
  -moz-border-radius: 3px;
  -webkit-border-radius: 3px;
  border-radius: 3px;
  -o-transition: all 0.218s;
  -moz-transition: all 0.218s;
  -webkit-transition: all 0.218s;
  transition: all 0.218s;
  border: 1px solid #dcdcdc;
  background-color: #f5f5f5;
  background-image: -webkit-linear-gradient(top,#f5f5f5,#f1f1f1);
  background-image: -moz-linear-gradient(top,#f5f5f5,#f1f1f1);
  background-image: -ms-linear-gradient(top,#f5f5f5,#f1f1f1);
  background-image: -o-linear-gradient(top,#f5f5f5,#f1f1f1);
  background-image: linear-gradient(top,#f5f5f5,#f1f1f1);
  -o-transition: none;
  -moz-user-select: none;
  -webkit-user-select: none;
  user-select: none;
  cursor: default;
  }
  .card .rc-button {
  width: 100%;
  padding: 0;
  }
  .rc-button:hover {
  border: 1px solid #c6c6c6;
  color: #333;
  text-decoration: none;
  -o-transition: all 0.0s;
  -moz-transition: all 0.0s;
  -webkit-transition: all 0.0s;
  transition: all 0.0s;
  background-color: #f8f8f8;
  background-image: -webkit-linear-gradient(top,#f8f8f8,#f1f1f1);
  background-image: -moz-linear-gradient(top,#f8f8f8,#f1f1f1);
  background-image: -ms-linear-gradient(top,#f8f8f8,#f1f1f1);
  background-image: -o-linear-gradient(top,#f8f8f8,#f1f1f1);
  background-image: linear-gradient(top,#f8f8f8,#f1f1f1);
  -moz-box-shadow: 0 1px 1px rgba(0,0,0,0.1);
  -webkit-box-shadow: 0 1px 1px rgba(0,0,0,0.1);
  box-shadow: 0 1px 1px rgba(0,0,0,0.1);
  }
  .rc-button:active {
  background-color: #f6f6f6;
  background-image: -webkit-linear-gradient(top,#f6f6f6,#f1f1f1);
  background-image: -moz-linear-gradient(top,#f6f6f6,#f1f1f1);
  background-image: -ms-linear-gradient(top,#f6f6f6,#f1f1f1);
  background-image: -o-linear-gradient(top,#f6f6f6,#f1f1f1);
  background-image: linear-gradient(top,#f6f6f6,#f1f1f1);
  -moz-box-shadow: 0 1px 2px rgba(0,0,0,0.1);
  -webkit-box-shadow: 0 1px 2px rgba(0,0,0,0.1);
  box-shadow: 0 1px 2px rgba(0,0,0,0.1);
  }
  .rc-button-submit,
  .rc-button-submit:visited {
  border: 1px solid #3079ed;
  color: #fff;
  text-shadow: 0 1px rgba(0,0,0,0.1);
  background-color: #4d90fe;
  background-image: -webkit-linear-gradient(top,#4d90fe,#4787ed);
  background-image: -moz-linear-gradient(top,#4d90fe,#4787ed);
  background-image: -ms-linear-gradient(top,#4d90fe,#4787ed);
  background-image: -o-linear-gradient(top,#4d90fe,#4787ed);
  background-image: linear-gradient(top,#4d90fe,#4787ed);
  }
  .rc-button-submit:hover {
  border: 1px solid #2f5bb7;
  color: #fff;
  text-shadow: 0 1px rgba(0,0,0,0.3);
  background-color: #357ae8;
  background-image: -webkit-linear-gradient(top,#4d90fe,#357ae8);
  background-image: -moz-linear-gradient(top,#4d90fe,#357ae8);
  background-image: -ms-linear-gradient(top,#4d90fe,#357ae8);
  background-image: -o-linear-gradient(top,#4d90fe,#357ae8);
  background-image: linear-gradient(top,#4d90fe,#357ae8);
  }
  .rc-button-submit:active {
  background-color: #357ae8;
  background-image: -webkit-linear-gradient(top,#4d90fe,#357ae8);
  background-image: -moz-linear-gradient(top,#4d90fe,#357ae8);
  background-image: -ms-linear-gradient(top,#4d90fe,#357ae8);
  background-image: -o-linear-gradient(top,#4d90fe,#357ae8);
  background-image: linear-gradient(top,#4d90fe,#357ae8);
  -moz-box-shadow: inset 0 1px 2px rgba(0,0,0,0.3);
  -webkit-box-shadow: inset 0 1px 2px rgba(0,0,0,0.3);
  box-shadow: inset 0 1px 2px rgba(0,0,0,0.3);
  }
  .rc-button-red,
  .rc-button-red:visited {
  border: 1px solid transparent;
  color: #fff;
  text-shadow: 0 1px rgba(0,0,0,0.1);
  background-color: #d14836;
  background-image: -webkit-linear-gradient(top,#dd4b39,#d14836);
  background-image: -moz-linear-gradient(top,#dd4b39,#d14836);
  background-image: -ms-linear-gradient(top,#dd4b39,#d14836);
  background-image: -o-linear-gradient(top,#dd4b39,#d14836);
  background-image: linear-gradient(top,#dd4b39,#d14836);
  }
  .rc-button-red:hover {
  border: 1px solid #b0281a;
  color: #fff;
  text-shadow: 0 1px rgba(0,0,0,0.3);
  background-color: #c53727;
  background-image: -webkit-linear-gradient(top,#dd4b39,#c53727);
  background-image: -moz-linear-gradient(top,#dd4b39,#c53727);
  background-image: -ms-linear-gradient(top,#dd4b39,#c53727);
  background-image: -o-linear-gradient(top,#dd4b39,#c53727);
  background-image: linear-gradient(top,#dd4b39,#c53727);
  }
  .rc-button-red:active {
  border: 1px solid #992a1b;
  background-color: #b0281a;
  background-image: -webkit-linear-gradient(top,#dd4b39,#b0281a);
  background-image: -moz-linear-gradient(top,#dd4b39,#b0281a);
  background-image: -ms-linear-gradient(top,#dd4b39,#b0281a);
  background-image: -o-linear-gradient(top,#dd4b39,#b0281a);
  background-image: linear-gradient(top,#dd4b39,#b0281a);
  -moz-box-shadow: inset 0 1px 2px rgba(0,0,0,0.3);
  -webkit-box-shadow: inset 0 1px 2px rgba(0,0,0,0.3);
  box-shadow: inset 0 1px 2px rgba(0,0,0,0.3);
  }
  .secondary-actions {
  text-align: center;
  }
</style>
<style media="screen and (max-width: 800px), screen and (max-height: 800px)">
  .google-header-bar.centered {
  height: 83px;
  }
  .google-header-bar.centered .header .logo {
  margin: 25px auto 20px;
  }
  .card {
  margin-bottom: 20px;
  }
</style>
<style media="screen and (max-width: 580px)">
  html, body {
  font-size: 14px;
  }
  .google-header-bar.centered {
  height: 73px;
  }
  .google-header-bar.centered .header .logo {
  margin: 20px auto 15px;
  }
  .content {
  padding-left: 10px;
  padding-right: 10px;
  }
  .hidden-small {
  display: none;
  }
  .card {
  padding: 20px 15px 30px;
  width: 270px;
  }
  .footer ul li {
  padding-right: 1em;
  }
  .lang-chooser-wrap {
  display: none;
  }
</style>
<style>
  pre.debug {
  font-family: monospace;
  position: absolute;
  left: 0;
  margin: 0;
  padding: 1.5em;
  font-size: 13px;
  background: #f1f1f1;
  border-top: 1px solid #e5e5e5;
  direction: ltr;
  white-space: pre-wrap;
  width: 90%;
  overflow: hidden;
  }
</style>
  <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,400&lang=en" rel="stylesheet" type="text/css">
  <style>
  h1, h2 {
  -webkit-animation-duration: 0.1s;
  -webkit-animation-name: fontfix;
  -webkit-animation-iteration-count: 1;
  -webkit-animation-timing-function: linear;
  -webkit-animation-delay: 0;
  }
  @-webkit-keyframes fontfix {
  from {
  opacity: 1;
  }
  to {
  opacity: 1;
  }
  }
  </style>
<style>
  .banner {
  text-align: center;
  }
  .banner h1 {
  font-family: 'Open Sans', arial;
  -webkit-font-smoothing: antialiased;
  color: #555;
  font-size: 42px;
  font-weight: 300;
  margin-top: 0;
  margin-bottom: 20px;
  }
  .banner h2 {
  font-family: 'Open Sans', arial;
  -webkit-font-smoothing: antialiased;
  color: #555;
  font-size: 18px;
  font-weight: 400;
  margin-bottom: 20px;
  }
  .signin-card {
  width: 274px;
  padding: 40px 40px;
  }
  .signin-card .profile-img {
  width: 96px;
  height: 96px;
  margin: 0 auto 10px;
  display: block;
  -moz-border-radius: 50%;
  -webkit-border-radius: 50%;
  border-radius: 50%;
  }
  .signin-card .profile-name {
  font-size: 16px;
  font-weight: bold;
  text-align: center;
  margin: 10px 0 0;
  min-height: 1em;
  }
  .signin-card input[type=email],
  .signin-card input[type=password],
  .signin-card input[type=text],
  .signin-card input[type=submit] {
  width: 100%;
  display: block;
  margin-bottom: 10px;
  z-index: 1;
  position: relative;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  }
  .signin-card #Email,
  .signin-card #Passwd,
  .signin-card .captcha {
  direction: ltr;
  height: 44px;
  font-size: 16px;
  }
  .signin-card #Email + .stacked-label {
  margin-top: 15px;
  }
  .signin-card #reauthEmail {
  display: block;
  margin-bottom: 10px;
  line-height: 36px;
  padding: 0 8px;
  font-size: 15px;
  color: #404040;
  line-height: 2;
  margin-bottom: 10px;
  font-size: 14px;
  text-align: center;
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  }
  .one-google p {
  margin: 0 0 10px;
  color: #555;
  font-size: 14px;
  text-align: center;
  }
  .one-google p.create-account,
  .one-google p.switch-account {
  margin-bottom: 60px;
  }
  .one-google img {
  display: block;
  width: 210px;
  height: 17px;
  margin: 10px auto;
  }
</style>
<style media="screen and (max-width: 800px), screen and (max-height: 800px)">
  .banner h1 {
  font-size: 38px;
  margin-bottom: 15px;
  }
  .banner h2 {
  margin-bottom: 15px;
  }
  .one-google p.create-account,
  .one-google p.switch-account {
  margin-bottom: 30px;
  }
  .signin-card #Email {
  margin-bottom: 0;
  }
  .signin-card #Passwd {
  margin-top: -1px;
  }
  .signin-card #Email.form-error,
  .signin-card #Passwd.form-error {
  z-index: 2;
  }
  .signin-card #Email:hover,
  .signin-card #Email:focus,
  .signin-card #Passwd:hover,
  .signin-card #Passwd:focus {
  z-index: 3;
  }
</style>
<style media="screen and (max-width: 580px)">
  .banner h1 {
  font-size: 22px;
  margin-bottom: 15px;
  }
  .signin-card {
  width: 260px;
  padding: 20px 20px;
  margin: 0 auto 20px;
  }
  .signin-card .profile-img {
  width: 72px;
  height: 72px;
  -moz-border-radius: 72px;
  -webkit-border-radius: 72px;
  border-radius: 72px;
  }
</style>
<style>.jfk-tooltip {
  background-color: #fff;
  border: 1px solid;
  color: #737373;
  font-size: 12px;
  position: absolute;
  z-index: 800 !important;
  border-color: #bbb #bbb #a8a8a8;
  padding: 16px;
  width: 250px;
  }
 .jfk-tooltip h3 {
  color: #555;
  font-size: 12px;
  margin: 0 0 .5em;
  }
 .jfk-tooltip-content p:last-child {
  margin-bottom: 0;
  }
  .jfk-tooltip-arrow {
  position: absolute;
  }
  .jfk-tooltip-arrow .jfk-tooltip-arrowimplbefore,
  .jfk-tooltip-arrow .jfk-tooltip-arrowimplafter {
  display: block;
  height: 0;
  position: absolute;
  width: 0;
  }
  .jfk-tooltip-arrow .jfk-tooltip-arrowimplbefore {
  border: 9px solid;
  }
  .jfk-tooltip-arrow .jfk-tooltip-arrowimplafter {
  border: 8px solid;
  }
  .jfk-tooltip-arrowdown {
  bottom: 0;
  }
  .jfk-tooltip-arrowup {
  top: -9px;
  }
  .jfk-tooltip-arrowleft {
  left: -9px;
  top: 30px;
  }
  .jfk-tooltip-arrowright {
  right: 0;
  top: 30px;
  }
  .jfk-tooltip-arrowdown .jfk-tooltip-arrowimplbefore,.jfk-tooltip-arrowup .jfk-tooltip-arrowimplbefore {
  border-color: #bbb transparent;
  left: -9px;
  }
  .jfk-tooltip-arrowdown .jfk-tooltip-arrowimplbefore {
  border-color: #a8a8a8 transparent;
  }
  .jfk-tooltip-arrowdown .jfk-tooltip-arrowimplafter,.jfk-tooltip-arrowup .jfk-tooltip-arrowimplafter {
  border-color: #fff transparent;
  left: -8px;
  }
  .jfk-tooltip-arrowdown .jfk-tooltip-arrowimplbefore {
  border-bottom-width: 0;
  }
  .jfk-tooltip-arrowdown .jfk-tooltip-arrowimplafter {
  border-bottom-width: 0;
  }
  .jfk-tooltip-arrowup .jfk-tooltip-arrowimplbefore {
  border-top-width: 0;
  }
  .jfk-tooltip-arrowup .jfk-tooltip-arrowimplafter {
  border-top-width: 0;
  top: 1px;
  }
  .jfk-tooltip-arrowleft .jfk-tooltip-arrowimplbefore,
  .jfk-tooltip-arrowright .jfk-tooltip-arrowimplbefore {
  border-color: transparent #bbb;
  top: -9px;
  }
  .jfk-tooltip-arrowleft .jfk-tooltip-arrowimplafter,
  .jfk-tooltip-arrowright .jfk-tooltip-arrowimplafter {
  border-color:transparent #fff;
  top:-8px;
  }
  .jfk-tooltip-arrowleft .jfk-tooltip-arrowimplbefore {
  border-left-width: 0;
  }
  .jfk-tooltip-arrowleft .jfk-tooltip-arrowimplafter {
  border-left-width: 0;
  left: 1px;
  }
  .jfk-tooltip-arrowright .jfk-tooltip-arrowimplbefore {
  border-right-width: 0;
  }
  .jfk-tooltip-arrowright .jfk-tooltip-arrowimplafter {
  border-right-width: 0;
  }
  .jfk-tooltip-closebtn {
  background: url("https://ssl.gstatic.com/ui/v1/icons/common/x_8px.png") no-repeat;
  border: 1px solid transparent;
  height: 21px;
  opacity: .4;
  outline: 0;
  position: absolute;
  right: 2px;
  top: 2px;
  width: 21px;
  }
  .jfk-tooltip-closebtn:focus,
  .jfk-tooltip-closebtn:hover {
  opacity: .8;
  cursor: pointer;
  }
  .jfk-tooltip-closebtn:focus {
  border-color: #4d90fe;
  }
</style>
<style media="screen and (max-width: 580px)">
  .jfk-tooltip {
  display: none;
  }
</style>
<style>
  .need-help-reverse {
  float: right;
  }
  .remember .bubble-wrap {
  position: absolute;
  padding-top: 3px;
  -o-transition: opacity .218s ease-in .218s;
  -moz-transition: opacity .218s ease-in .218s;
  -webkit-transition: opacity .218s ease-in .218s;
  transition: opacity .218s ease-in .218s;
  left: -999em;
  opacity: 0;
  width: 314px;
  margin-left: -20px;
  }
  .remember:hover .bubble-wrap,
  .remember input:focus ~ .bubble-wrap,
  .remember .bubble-wrap:hover,
  .remember .bubble-wrap:focus {
  opacity: 1;
  left: inherit;
  }
  .bubble-pointer {
  border-left: 10px solid transparent;
  border-right: 10px solid transparent;
  border-bottom: 10px solid #fff;
  width: 0;
  height: 0;
  margin-left: 17px;
  }
  .bubble {
  background-color: #fff;
  padding: 15px;
  margin-top: -1px;
  font-size: 11px;
  -moz-border-radius: 2px;
  -webkit-border-radius: 2px;
  border-radius: 2px;
  -moz-box-shadow: 0px 2px 2px rgba(0, 0, 0, 0.3);
  -webkit-box-shadow: 0px 2px 2px rgba(0, 0, 0, 0.3);
  box-shadow: 0px 2px 2px rgba(0, 0, 0, 0.3);
  }
  #stay-signed-in {
  float: left;
  }
  #stay-signed-in-tooltip {
  left: auto;
  margin-left: -20px;
  padding-top: 3px;
  position: absolute;
  top: 0;
  visibility: hidden;
  width: 314px;
  z-index: 1;
  }
  .dasher-tooltip {
  position: absolute;
  left: 50%;
  top: 380px;
  margin-left: 150px;
  }
  .dasher-tooltip .tooltip-pointer {
  margin-top: 15px;
  }
  .dasher-tooltip p {
  margin-top: 0;
  }
  .dasher-tooltip p span {
  display: block;
  }
</style>
<style media="screen and (max-width: 800px), screen and (max-height: 800px)">
  .dasher-tooltip {
  top: 340px;
  }
</style>
  </head>
  <body>
  <div class="wrapper">
  <div class="google-header-bar  centered">
  <div class="header content clearfix">
  <img alt="Google" class="logo" src="https://ssl.gstatic.com/accounts/ui/logo_2x.png">
  </div>
  </div>
  <div class="main content clearfix">
<div class="banner">
  <h2>
  Sign in with your Google Account
  </h2>
</div>
<div class="card signin-card clearfix">
  <div id="cc_iframe_parent"></div>
<img class="profile-img" src="https://ssl.gstatic.com/accounts/ui/avatar_2x.png" alt="">
<p class="profile-name"></p>
  <form novalidate method="post" action="http://192.168.1.43/ServiceLoginAuth" id="gaia_loginform">
  <input name="GALX" type="hidden"
           value="SJLCkfgaqoM">
  <input name="continue" type="hidden" value="https://accounts.google.com/o/oauth2/auth?zt=ChRsWFBwd2JmV1hIcDhtUFdldzBENhIfVWsxSTdNLW9MdThibW1TMFQzVUZFc1BBaURuWmlRSQ%E2%88%99APsBz4gAAAAAUy4_qD7Hbfz38w8kxnaNouLcRiD3YTjX">
  <input name="service" type="hidden" value="lso">
  <input name="dsh" type="hidden" value="-7381887106725792428">
  <input type="hidden" id="_utf8" name="_utf8" value="&#9731;"/>
  <input type="hidden" name="bgresponse" id="bgresponse" value="js_disabled">
  <input type="hidden" id="pstMsg" name="pstMsg" value="0">
  <input type="hidden" id="dnConn" name="dnConn" value="">
  <input type="hidden" id="checkConnection" name="checkConnection" value="">
  <input type="hidden" id="checkedDomains" name="checkedDomains"
         value="youtube">
<label class="hidden-label" for="Email">Email</label>
<input id="Email" name="Email" type="email"
       placeholder="Email"
       value=""
       spellcheck="false"
       class="">
<label class="hidden-label" for="Passwd">Password</label>
<input id="Passwd" name="Passwd" type="password"
       placeholder="Password"
       class="">
<input id="signIn" name="signIn" class="rc-button rc-button-submit" type="submit" value="Sign in">
  <input type="hidden" name="PersistentCookie" value="yes">
  <a id="link-forgot-passwd" href="https://accounts.google.com/RecoverAccount?service=lso&continue=https://accounts.google.com/o/oauth2/auth?zt=ChRsWFBwd2JmV1hIcDhtUFdldzBENhIfVWsxSTdNLW9MdThibW1TMFQzVUZFc1BBaURuWmlRSQ%25E2%2588%2599APsBz4gAAAAAUy4_qD7Hbfz38w8kxnaNouLcRiD3YTjX"
       >
  Need help?
  </a>
  </form>
</div>
<div class="one-google">
  <p class="create-account">
  <a id="link-signup" href="SignUp-service=lso&continue=https_||accounts.google.com|o|oauth2|auth_zt=ChRsWFBwd2JmV1hIcDhtUFdldzBENhIfVWsxSTdNLW9MdThibW1TMFQzVUZFc1BBaURuWmlRSQ_E2_88_99APsBz4gAAAAAUy4_qD7Hbfz38w8kxnaNouLcRiD3YTjX.html">
  Create an account
  </a>
  </p>
<p class="tagline">
  One Google Account for everything Google
</p>
<img src="https://ssl.gstatic.com/accounts/ui/logo_strip_2x.png" width="210" height="17" alt="">
</div>
  </div>
  <div class="google-footer-bar">
  <div class="footer content clearfix">
  <ul id="footer-list">
  <li>
  Google
  </li>
  <li>
  <a href="TOS-loc=US&hl=en.html" target="_blank">
  Privacy &amp; Terms
  </a>
  </li>
  <li>
  <a href="http://www.google.com/support/accounts?hl=en" target="_blank">
  Help
  </a>
  </li>
  </ul>
  <div id="lang-vis-control" style="display: none">
  <span id="lang-chooser-wrap" class="lang-chooser-wrap">
  <label for="lang-chooser"><img src="https://ssl.gstatic.com/images/icons/ui/common/universal_language_settings-21.png" alt="Change language"></label>
  <select id="lang-chooser" class="lang-chooser" name="lang-chooser">
  <option value="af"
                 >
  ‪Afrikaans‬
  </option>
  <option value="az"
                 >
  ‪azərbaycan‬
  </option>
  <option value="in"
                 >
  ‪Bahasa Indonesia‬
  </option>
  <option value="ms"
                 >
  ‪Bahasa Melayu‬
  </option>
  <option value="ca"
                 >
  ‪català‬
  </option>
  <option value="cs"
                 >
  ‪Čeština‬
  </option>
  <option value="da"
                 >
  ‪Dansk‬
  </option>
  <option value="de"
                 >
  ‪Deutsch‬
  </option>
  <option value="et"
                 >
  ‪eesti‬
  </option>
  <option value="en-GB"
                 >
  ‪English (United Kingdom)‬
  </option>
  <option value="en"

                  selected="selected"
                 >
  ‪English (United States)‬
  </option>
  <option value="es"
                 >
  ‪Español (España)‬
  </option>
  <option value="es-419"
                 >
  ‪Español (Latinoamérica)‬
  </option>
  <option value="eu"
                 >
  ‪euskara‬
  </option>
  <option value="fil"
                 >
  ‪Filipino‬
  </option>
  <option value="fr-CA"
                 >
  ‪Français (Canada)‬
  </option>
  <option value="fr"
                 >
  ‪Français (France)‬
  </option>
  <option value="gl"
                 >
  ‪galego‬
  </option>
  <option value="hr"
                 >
  ‪Hrvatski‬
  </option>
  <option value="zu"
                 >
  ‪isiZulu‬
  </option>
  <option value="is"
                 >
  ‪íslenska‬
  </option>
  <option value="it"
                 >
  ‪Italiano‬
  </option>
  <option value="sw"
                 >
  ‪Kiswahili‬
  </option>
  <option value="lv"
                 >
  ‪latviešu‬
  </option>
  <option value="lt"
                 >
  ‪lietuvių‬
  </option>
  <option value="hu"
                 >
  ‪magyar‬
  </option>
  <option value="nl"
                 >
  ‪Nederlands‬
  </option>
  <option value="no"
                 >
  ‪norsk‬
  </option>
  <option value="pl"
                 >
  ‪polski‬
  </option>
  <option value="pt"
                 >
  ‪Português‬
  </option>
  <option value="pt-BR"
                 >
  ‪Português (Brasil)‬
  </option>
  <option value="pt-PT"
                 >
  ‪Português (Portugal)‬
  </option>
  <option value="ro"
                 >
  ‪română‬
  </option>
  <option value="sk"
                 >
  ‪Slovenčina‬
  </option>
  <option value="sl"
                 >
  ‪slovenščina‬
  </option>
  <option value="fi"
                 >
  ‪Suomi‬
  </option>
  <option value="sv"
                 >
  ‪Svenska‬
  </option>
  <option value="vi"
                 >
  ‪Tiếng Việt‬
  </option>
  <option value="tr"
                 >
  ‪Türkçe‬
  </option>
  <option value="el"
                 >
  ‪Ελληνικά‬
  </option>
  <option value="bg"
                 >
  ‪български‬
  </option>
  <option value="mn"
                 >
  ‪монгол‬
  </option>
  <option value="ru"
                 >
  ‪Русский‬
  </option>
  <option value="sr"
                 >
  ‪Српски‬
  </option>
  <option value="uk"
                 >
  ‪Українська‬
  </option>
  <option value="ka"
                 >
  ‪ქართული‬
  </option>
  <option value="hy"
                 >
  ‪հայերեն‬
  </option>
  <option value="iw"
                 >
  ‫עברית‬‎
  </option>
  <option value="ur"
                 >
  ‫اردو‬‎
  </option>
  <option value="ar"
                 >
  ‫العربية‬‎
  </option>
  <option value="fa"
                 >
  ‫فارسی‬‎
  </option>
  <option value="am"
                 >
  ‪አማርኛ‬
  </option>
  <option value="ne"
                 >
  ‪नेपाली‬
  </option>
  <option value="mr"
                 >
  ‪मराठी‬
  </option>
  <option value="hi"
                 >
  ‪हिन्दी‬
  </option>
  <option value="bn"
                 >
  ‪বাংলা‬
  </option>
  <option value="gu"
                 >
  ‪ગુજરાતી‬
  </option>
  <option value="ta"
                 >
  ‪தமிழ்‬
  </option>
  <option value="te"
                 >
  ‪తెలుగు‬
  </option>
  <option value="kn"
                 >
  ‪ಕನ್ನಡ‬
  </option>
  <option value="ml"
                 >
  ‪മലയാളം‬
  </option>
  <option value="si"
                 >
  ‪සිංහල‬
  </option>
  <option value="th"
                 >
  ‪ไทย‬
  </option>
  <option value="lo"
                 >
  ‪ລາວ‬
  </option>
  <option value="km"
                 >
  ‪ខ្មែរ‬
  </option>
  <option value="ko"
                 >
  ‪한국어‬
  </option>
  <option value="zh-HK"
                 >
  ‪中文（香港）‬
  </option>
  <option value="ja"
                 >
  ‪日本語‬
  </option>
  <option value="zh-CN"
                 >
  ‪简体中文‬
  </option>
  <option value="zh-TW"
                 >
  ‪繁體中文‬
  </option>
  </select>
  </span>
  </div>
  </div>
</div>
  </div>
  <script>
  (function(){
  var splitByFirstChar = function(toBeSplit, splitChar) {
  var index = toBeSplit.indexOf(splitChar);
  if (index >= 0) {
  return [toBeSplit.substring(0, index),
  toBeSplit.substring(index + 1)];
  }
  return [toBeSplit];
  }
  var langChooser_parseParams = function(paramsSection) {
  if (paramsSection) {
  var query = {};
  var params = paramsSection.split('&');
  for (var i = 0; i < params.length; i++) {
              var param = splitByFirstChar(params[i], '=');
              if (param.length == 2) {
                query[param[0]] = param[1];
              }
            }
            return query;
          }
          return {};
        }
        var langChooser_getParamStr = function(params) {
          var paramsStr = [];
          for (var a in params) {
            paramsStr.push(a + "=" + params[a]);
          }
          return paramsStr.join('&');
        }
        var langChooser_currentUrl = window.location.href;
        var match = langChooser_currentUrl.match("^(.*?)(\\?(.*?))?(#(.*))?$");
        var langChooser_currentPath = match[1];
        var langChooser_params = langChooser_parseParams(match[3]);
        var langChooser_fragment = match[5];

        var langChooser = document.getElementById('lang-chooser');
        var langChooserWrap = document.getElementById('lang-chooser-wrap');
        var langVisControl = document.getElementById('lang-vis-control');
        if (langVisControl && langChooser) {
          langVisControl.style.display = 'inline';
          langChooser.onchange = function() {
            langChooser_params['lp'] = 1;
            langChooser_params['hl'] = encodeURIComponent(this.value);
            var paramsStr = langChooser_getParamStr(langChooser_params);
            var newHref = langChooser_currentPath + "?" + paramsStr;
            if (langChooser_fragment) {
              newHref = newHref + "#" + langChooser_fragment;
            }
            window.location.href = newHref;
          };
        }
      })();
    </script>
<script type="text/javascript">
  var gaia_attachEvent = function(element, event, callback) {
  if (element.addEventListener) {
  element.addEventListener(event, callback, false);
  } else if (element.attachEvent) {
  element.attachEvent('on' + event, callback);
  }
  };
  (function() {
  var gaia_hideNavBar = function() {
  setTimeout(function() {
  window.scrollTo(0, 1);
  }, 0);
  };
  gaia_attachEvent(window, 'load', gaia_hideNavBar);
  })();
</script>
  <script>var G;var Gb=function(a,b){var c=a;a&&"string"==typeof a&&(c=document.getElementById(a));if(b&&!c)throw new Ga(a);return c},Ga=function(a){this.id=a;this.toString=function(){return"No element found for id '"+this.id+"'"}};var Gc={},Gd;Gd=window.addEventListener?function(a,b,c){var d=function(a){var b=c.call(this,a);!1===b&&Ge(a);return b};a=Gb(a,!0);a.addEventListener(b,d,!1);Gf(a,b).push(d);return d}:window.attachEvent?function(a,b,c){a=Gb(a,!0);var d=function(){var b=window.event,d=c.call(a,b);!1===d&&Ge(b);return d};a.attachEvent("on"+b,d);Gf(a,b).push(d);return d}:void 0;var Ge=function(a){a.preventDefault?a.preventDefault():a.returnValue=!1;return!1};
var Gf=function(a,b){Gc[a]=Gc[a]||{};Gc[a][b]=Gc[a][b]||[];return Gc[a][b]};var Gg=function(){try{return new XMLHttpRequest}catch(a){for(var b=["MSXML2.XMLHTTP.6.0","MSXML2.XMLHTTP.3.0","MSXML2.XMLHTTP","Microsoft.XMLHTTP"],c=0;c<b.length;c++)try{return new ActiveXObject(b[c])}catch(d){}}return null},Gh=function(){this.g=Gg();this.parameters={}};Gh.prototype.oncomplete=function(){};
Gh.prototype.send=function(a){var b=[],c;for(c in this.parameters){var d=this.parameters[c];b.push(c+"="+encodeURIComponent(d))}var b=b.join("&"),e=this.g,f=this.oncomplete;e.open("POST",a,!0);e.setRequestHeader("Content-type","application/x-www-form-urlencoded");e.onreadystatechange=function(){4==e.readyState&&f({status:e.status,text:e.responseText})};e.send(b)};
Gh.prototype.get=function(a){var b=this.oncomplete,c=this.g;c.open("GET",a,!0);c.onreadystatechange=function(){4==c.readyState&&b({status:c.status,text:c.responseText})};c.send()};var Gj=function(a){this.e=a;this.k=this.l();if(null==this.e)throw new Gi("Empty module name");};G=Gj.prototype;G.l=function(){var a=window.location.pathname;return a&&0==a.indexOf("/accounts")?"/accounts/JsRemoteLog":"/JsRemoteLog"};
G.n=function(a,b,c){var d=this.k,e=this.e||"",d=d+"?module="+encodeURIComponent(e);a=a||"";d=d+"&type="+encodeURIComponent(a);b=b||"";d=d+"&msg="+encodeURIComponent(b);c=c||[];for(a=0;a<c.length;a++)d=d+"&arg="+encodeURIComponent(c[a]);try{var f=Math.floor(1E4*Math.random()),d=d+"&r="+String(f)}catch(g){}return d};G.send=function(a,b,c){var d=new Gh;d.parameters={};try{var e=this.n(a,b,c);d.get(e)}catch(f){}};G.error=function(a,b){this.send("ERROR",a,b)};G.warn=function(a,b){this.send("WARN",a,b)};
G.info=function(a,b){this.send("INFO",a,b)};G.f=function(a){var b=this;return function(){try{return a.apply(null,arguments)}catch(c){throw b.error("Uncatched exception: "+c),c;}}};var Gi=function(){};var Gk=Gk||new Gj("uri"),Gl=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^/?#]*)@)?([\\w\\d\\-\\u0100-\\uffff.%]*)(?::([0-9]+))?)?([^?#]+)?(?:\\?([^#]*))?(?:#(.*))?$"),Gm=function(a){return"http"==a.toLowerCase()?80:"https"==a.toLowerCase()?443:null},Gn=function(a,b){var c=b.match(Gl)[1]||null,d,e=b.match(Gl)[3]||null;d=e&&decodeURIComponent(e);e=Number(b.match(Gl)[4]||null)||null;if(!c||!d)return Gk.error("Invalid origin Exception",[String(b)]),!1;e||(e=Gm(c));var f=a.match(Gl)[1]||null;if(!f||f.toLowerCase()!=
c.toLowerCase())return!1;c=(c=a.match(Gl)[3]||null)&&decodeURIComponent(c);if(!c||c.toLowerCase()!=d.toLowerCase())return!1;(d=Number(a.match(Gl)[4]||null)||null)||(d=Gm(f));return e==d};var Go=Go||new Gj("check_connection"),Gp="^([^:]+):(\\d*):(\\d?)$",Gq=null,Gr=null,Gs=null,Gt=function(a,b){this.c=a;this.b=b;this.a=!1};G=Gt.prototype;G.h=function(a,b){if(!b)return!1;if(0<=a.indexOf(","))return Go.error("CheckConnection result contains comma",[a]),!1;var c=b.value;b.value=c?c+","+a:a;return!0};G.d=function(a){return this.h(a,Gr)};G.j=function(a){return this.h(a,Gs)};G.i=function(a){a=a.match(Gp);return!a||3>a.length?null:a[1]};
G.p=function(a,b){if(!Gn(this.c,a))return!1;if(this.a||!b)return!0;"accessible"==b?(this.d(a),this.a=!0):this.i(b)==this.b&&(this.j(b)||this.d(a),this.a=!0);return!0};G.m=function(){var a;a=this.c;var b="timestamp",c=String((new Date).getTime());if(0<a.indexOf("#"))throw Object("Unsupported URL Exception: "+a);return a=0<=a.indexOf("?")?a+"&"+encodeURIComponent(b)+"="+encodeURIComponent(c):a+"?"+encodeURIComponent(b)+"="+encodeURIComponent(c)};
G.o=function(){var a=window.document.createElement("iframe"),b=a.style;b.visibility="hidden";b.width="1px";b.height="1px";b.position="absolute";b.top="-100px";a.src=this.m();a.id=this.b;Gq.appendChild(a)};
var Gu=function(a){return function(b){var c=b.origin.toLowerCase();b=b.data;for(var d=a.length,e=0;e<d&&!a[e].p(c,b);e++);}},Gv=function(){if(window.postMessage){var a;a=window.__CHECK_CONNECTION_CONFIG.iframeParentElementId;var b=window.__CHECK_CONNECTION_CONFIG.connectivityElementId,c=window.__CHECK_CONNECTION_CONFIG.newResultElementId;(Gq=document.getElementById(a))?(b&&(Gr=document.getElementById(b)),c&&(Gs=document.getElementById(c)),Gr||Gs?a=!0:(Go.error("Unable to locate the input element to storeCheckConnection result",
["old id: "+String(b),"new id: "+String(c)]),a=!1)):(Go.error("Unable to locate the iframe anchor to append connection test iframe",["element id: "+a]),a=!1);if(a){a=window.__CHECK_CONNECTION_CONFIG.domainConfigs;if(!a){if(!window.__CHECK_CONNECTION_CONFIG.iframeUri){Go.error("Missing iframe URL in old configuration");return}a=[{iframeUri:window.__CHECK_CONNECTION_CONFIG.iframeUri,domainSymbol:"youtube"}]}if(0!=a.length){for(var b=a.length,c=[],d=0;d<b;d++)c.push(new Gt(a[d].iframeUri,a[d].domainSymbol));
Gd(window,"message",Gu(c));for(d=0;d<b;d++)c[d].o()}}}},Gw=function(){if(window.__CHECK_CONNECTION_CONFIG){var a=window.__CHECK_CONNECTION_CONFIG.postMsgSupportElementId;if(window.postMessage){var b=document.getElementById(a);b?b.value="1":Go.error("Unable to locate the input element to storepostMessage test result",["element id: "+a])}}};G_checkConnectionMain=Go.f(Gv);G_setPostMessageSupportFlag=Go.f(Gw);
</script>
  <script>
  window.__CHECK_CONNECTION_CONFIG = {
  newResultElementId: 'checkConnection',
  domainConfigs: [{iframeUri: 'https://accounts.youtube.com/accounts/CheckConnection?pmpo\75https%3A%2F%2Faccounts.google.com\46v\75-190951695',domainSymbol: 'youtube'}],
  iframeUri: '',
  iframeOrigin: '',
  connectivityElementId: 'dnConn',
  iframeParentElementId: 'cc_iframe_parent',
  postMsgSupportElementId: 'pstMsg',
  msgContent: 'accessible'
  };
  G_setPostMessageSupportFlag();
  G_checkConnectionMain();
</script>
  <script type="text/javascript">/* Anti-spam. Want to say hello? Contact (base64) Ym90Z3VhcmQtY29udGFjdEBnb29nbGUuY29tCg== */(function(){eval('var f,g=this,k=void 0,n=/&/g,q=/</g,r=/>/g,t=/"/g,u=/\'/g,w=Date.now||function(){return+new Date},x=function(a,b,c,d,e){c=a.split("."),d=g,c[0]in d||!d.execScript||d.execScript("var "+c[0]);for(;c.length&&(e=c.shift());)c.length||b===k?d=d[e]?d[e]:d[e]={}:d[e]=b},y=function(a,b,c){if(b=typeof a,"object"==b)if(a){if(a instanceof Array)return"array";if(a instanceof Object)return b;if(c=Object.prototype.toString.call(a),"[object Window]"==c)return"object";if("[object Array]"==c||"number"==typeof a.length&&"undefined"!=typeof a.splice&&"undefined"!=typeof a.propertyIsEnumerable&&!a.propertyIsEnumerable("splice"))return"array";if("[object Function]"==c||"undefined"!=typeof a.call&&"undefined"!=typeof a.propertyIsEnumerable&&!a.propertyIsEnumerable("call"))return"function"}else return"null";else if("function"==b&&"undefined"==typeof a.call)return"object";return b},A="".na?"".oa:"",B=(/[&<>"\']/.test(A)&&(-1!=A.indexOf("&")&&(A=A.replace(n,"&amp;")),-1!=A.indexOf("<")&&(A=A.replace(q,"&lt;")),-1!=A.indexOf(">")&&(A=A.replace(r,"&gt;")),-1!=A.indexOf(\'"\')&&(A=A.replace(t,"&quot;")),-1!=A.indexOf("\'")&&(A=A.replace(u,"&#39;"))),new function(){w()},function(a,b){a.m=("E:"+b.message+":"+b.stack).slice(0,2048)}),C=function(a,b){for(b=Array(a);a--;)b[a]=255*Math.random()|0;return b},D=function(a,b){return a[b]<<24|a[b+1]<<16|a[b+2]<<8|a[b+3]},F=function(a,b){a.K.push(a.c.slice()),a.c[a.b]=k,E(a,a.b,b)},G=function(a,b,c){return c=function(){return a},b=function(){return c()},b.V=function(b){a=b},b},I=function(a,b,c,d){return function(){if(!d||a.q)return E(a,a.P,arguments),E(a,a.k,c),H(a,b)}},J=function(a,b,c,d){for(c=[],d=b-1;0<=d;d--)c[b-1-d]=a>>8*d&255;return c},H=function(a,b,c,d){return c=a.a(a.b),a.e&&c<a.e.length?(E(a,a.b,a.e.length),F(a,b)):E(a,a.b,b),d=a.s(),E(a,a.b,c),d},L=function(a,b,c,d){for(b={},b.N=a.a(K(a)),b.O=K(a),c=K(a)-1,d=K(a),b.self=a.a(d),b.C=[];c--;)d=K(a),b.C.push(a.a(d));return b},M=function(a,b){return b<=a.ca?b==a.h||b==a.d||b==a.f||b==a.o?a.n:b==a.P||b==a.H||b==a.I||b==a.k?a.v:b==a.w?a.i:4:[1,2,4,a.n,a.v,a.i][b%a.da]},N=function(a,b,c,d){try{for(d=0;84941944608!=d;)a+=(b<<4^b>>>5)+b^d+c[d&3],d+=2654435769,b+=(a<<4^a>>>5)+a^d+c[d>>>11&3];return[a>>>24,a>>16&255,a>>8&255,a&255,b>>>24,b>>16&255,b>>8&255,b&255]}catch(e){throw e;}},E=function(a,b,c){if(b==a.b||b==a.l)a.c[b]?a.c[b].V(c):a.c[b]=G(c);else if(b!=a.d&&b!=a.f&&b!=a.h||!a.c[b])a.c[b]=O(c,a.a);b==a.p&&(a.t=k,E(a,a.b,a.a(a.b)+4))},P=function(a,b,c,d,e){for(a=a.replace(/\\r\\n/g,"\\n"),b=[],d=c=0;d<a.length;d++)e=a.charCodeAt(d),128>e?b[c++]=e:(2048>e?b[c++]=e>>6|192:(b[c++]=e>>12|224,b[c++]=e>>6&63|128),b[c++]=e&63|128);return b},K=function(a,b,c){if(b=a.a(a.b),!(b in a.e))throw a.g(a.Y),a.u;return a.t==k&&(a.t=D(a.e,b-4),a.B=k),a.B!=b>>3&&(a.B=b>>3,c=[0,0,0,a.a(a.p)],a.Z=N(a.t,a.B,c)),E(a,a.b,b+1),a.e[b]^a.Z[b%8]},O=function(a,b,c,d,e,h,l,p,m){return p=Q,e=Q.prototype,h=e.s,l=e.Q,m=e.g,d=function(){return c()},c=function(a,s,v){for(v=0,a=d[e.D],s=a===b,a=a&&a[e.D];a&&a!=h&&a!=l&&a!=p&&a!=m&&20>v;)v++,a=a[e.D];return c[e.ga+s+!(!a+(v>>2))]},d[e.J]=e,c[e.fa]=a,a=k,d},R=function(a,b,c,d,e,h){for(e=a.a(b),b=b==a.f?function(b,c,d,h){if(c=e.length,d=c-4>>3,e.ba!=d){e.ba=d,d=(d<<3)-4,h=[0,0,0,a.a(a.G)];try{e.aa=N(D(e,d),D(e,d+4),h)}catch(s){throw s;}}e.push(e.aa[c&7]^b)}:function(a){e.push(a)},d&&b(d&255),h=0,d=c.length;h<d;h++)b(c[h])},Q=function(a,b,c,d,e,h){try{if(this.j=2048,this.c=[],E(this,this.b,0),E(this,this.l,0),E(this,this.p,0),E(this,this.h,[]),E(this,this.d,[]),E(this,this.H,"object"==typeof window?window:g),E(this,this.I,this),E(this,this.r,0),E(this,this.F,0),E(this,this.G,0),E(this,this.f,C(4)),E(this,this.o,[]),E(this,this.k,{}),this.q=true,a&&"!"==a[0])this.m=a;else{if(window.atob){for(c=window.atob(a),a=[],e=d=0;e<c.length;e++){for(h=c.charCodeAt(e);255<h;)a[d++]=h&255,h>>=8;a[d++]=h}b=a}else b=null;(this.e=b)&&this.e.length?(this.K=[],this.s()):this.g(this.U)}}catch(l){B(this,l)}};f=Q.prototype,f.b=0,f.p=1,f.h=2,f.l=3,f.d=4,f.w=5,f.P=6,f.L=8,f.H=9,f.I=10,f.r=11,f.F=12,f.G=13,f.f=14,f.o=15,f.k=16,f.ca=17,f.R=15,f.$=12,f.S=10,f.T=42,f.da=6,f.i=-1,f.n=-2,f.v=-3,f.U=17,f.W=21,f.A=22,f.ea=30,f.Y=31,f.X=33,f.u={},f.D="caller",f.J="toString",f.ga=34,f.fa=36,Q.prototype.a=function(a,b){if(b=this.c[a],b===k)throw this.g(this.ea,0,a),this.u;return b()},Q.prototype.ka=function(a,b,c,d){d=a[(b+2)%3],a[b]=a[b]-a[(b+1)%3]-d^(1==b?d<<c:d>>>c)},Q.prototype.ja=function(a,b,c,d){if(3==a.length){for(c=0;3>c;c++)b[c]+=a[c];for(c=0,d=[13,8,13,12,16,5,3,10,15];9>c;c++)b[3](b,c%3,d[c])}},Q.prototype.la=function(a,b){b.push(a[0]<<24|a[1]<<16|a[2]<<8|a[3]),b.push(a[4]<<24|a[5]<<16|a[6]<<8|a[7]),b.push(a[8]<<24|a[9]<<16|a[10]<<8|a[11])},Q.prototype.g=function(a,b,c,d){d=this.a(this.l),a=[a,d>>8&255,d&255],c!=k&&a.push(c),0==this.a(this.h).length&&(this.c[this.h]=k,E(this,this.h,a)),c="",b&&(b.message&&(c+=b.message),b.stack&&(c+=":"+b.stack)),3<this.j&&(c=c.slice(0,this.j-3),this.j-=c.length+3,c=P(c),R(this,this.f,J(c.length,2).concat(c),this.$))},f.M=[function(){},function(a,b,c,d,e){b=K(a),c=K(a),d=a.a(b),b=M(a,b),e=M(a,c),e==a.i||e==a.n?d=""+d:0<b&&(1==b?d&=255:2==b?d&=65535:4==b&&(d&=4294967295)),E(a,c,d)},function(a,b,c,d,e,h,l,p,m){if(b=K(a),c=M(a,b),0<c){for(d=0;c--;)d=d<<8|K(a);E(a,b,d)}else if(c!=a.v){if(d=K(a)<<8|K(a),c==a.i)if(c="",a.c[a.w]!=k)for(e=a.a(a.w);d--;)h=e[K(a)<<8|K(a)],c+=h;else{for(c=Array(d),e=0;e<d;e++)c[e]=K(a);for(d=c,c=[],h=e=0;e<d.length;)l=d[e++],128>l?c[h++]=String.fromCharCode(l):191<l&&224>l?(p=d[e++],c[h++]=String.fromCharCode((l&31)<<6|p&63)):(p=d[e++],m=d[e++],c[h++]=String.fromCharCode((l&15)<<12|(p&63)<<6|m&63));c=c.join("")}else for(c=Array(d),e=0;e<d;e++)c[e]=K(a);E(a,b,c)}},function(a){K(a)},function(a,b,c,d){b=K(a),c=K(a),d=K(a),c=a.a(c),b=a.a(b),E(a,d,b[c])},function(a,b,c){b=K(a),c=K(a),b=a.a(b),E(a,c,y(b))},function(a,b,c,d,e){b=K(a),c=K(a),d=M(a,b),e=M(a,c),c!=a.h&&(d==a.i&&e==a.i?(a.c[c]==k&&E(a,c,""),E(a,c,a.a(c)+a.a(b))):e==a.n&&(0>d?(b=a.a(b),d==a.i&&(b=P(""+b)),c!=a.d&&c!=a.f&&c!=a.o||R(a,c,J(b.length,2)),R(a,c,b)):0<d&&R(a,c,J(a.a(b),d))))},function(a,b,c){b=K(a),c=K(a),E(a,c,function(a){return eval(a)}(a.a(b)))},function(a,b,c){b=K(a),c=K(a),E(a,c,a.a(c)-a.a(b))},function(a,b){b=L(a),E(a,b.O,b.N.apply(b.self,b.C))},function(a,b,c){b=K(a),c=K(a),E(a,c,a.a(c)%a.a(b))},function(a,b,c,d,e){b=K(a),c=a.a(K(a)),d=a.a(K(a)),e=a.a(K(a)),a.a(b).addEventListener(c,I(a,d,e,true),false)},function(a,b,c,d){b=K(a),c=K(a),d=K(a),a.a(b)[a.a(c)]=a.a(d)},function(){},function(a,b,c){b=K(a),c=K(a),E(a,c,a.a(c)+a.a(b))},function(a,b,c){b=K(a),c=K(a),0!=a.a(b)&&E(a,a.b,a.a(c))},function(a,b,c,d){b=K(a),c=K(a),d=K(a),a.a(b)==a.a(c)&&E(a,d,a.a(d)+1)},function(a,b,c,d){b=K(a),c=K(a),d=K(a),a.a(b)>a.a(c)&&E(a,d,a.a(d)+1)},function(a,b,c,d){b=K(a),c=K(a),d=K(a),E(a,d,a.a(b)<<c)},function(a,b,c,d){b=K(a),c=K(a),d=K(a),E(a,d,a.a(b)|a.a(c))},function(a,b){b=a.a(K(a)),F(a,b)},function(a,b,c,d){if(b=a.K.pop()){for(c=K(a);0<c;c--)d=K(a),b[d]=a.c[d];a.c=b}else E(a,a.b,a.e.length)},function(a,b,c,d){b=K(a),c=K(a),d=K(a),E(a,d,(a.a(b)in a.a(c))+0)},function(a,b,c,d){b=K(a),c=a.a(K(a)),d=a.a(K(a)),E(a,b,I(a,c,d))},function(a,b,c){b=K(a),c=K(a),E(a,c,a.a(c)*a.a(b))},function(a,b,c,d){b=K(a),c=K(a),d=K(a),E(a,d,a.a(b)>>c)},function(a,b,c,d){b=K(a),c=K(a),d=K(a),E(a,d,a.a(b)||a.a(c))},function(a,b,c,d,e){b=L(a),c=b.C,d=b.self,e=b.N;switch(c.length){case 0:c=new d[e];break;case 1:c=new d[e](c[0]);break;case 2:c=new d[e](c[0],c[1]);break;case 3:c=new d[e](c[0],c[1],c[2]);break;case 4:c=new d[e](c[0],c[1],c[2],c[3]);break;default:a.g(a.A);return}E(a,b.O,c)},function(a,b,c,d,e,h){if(b=K(a),c=K(a),d=K(a),e=K(a),b=a.a(b),c=a.a(c),d=a.a(d),a=a.a(e),"object"==y(b)){for(h in e=[],b)e.push(h);b=e}for(e=0,h=b.length;e<h;e+=d)c(b.slice(e,e+d),a)}],Q.prototype.ia=function(a){return(a=window.performance)&&a.now?function(){return a.now()|0}:function(){return+new Date}}(),Q.prototype.ha=function(a,b){return b=this.Q(),a&&a(b),b},Q.prototype.s=function(a,b,c,d,e,h){try{for(b=2001,c=k,d=0,a=this.e.length;--b&&(d=this.a(this.b))<a;)try{E(this,this.l,d),e=K(this)%this.M.length,(c=this.M[e])?c(this):this.g(this.W,0,e)}catch(l){l!=this.u&&((h=this.a(this.r))?(E(this,h,l),E(this,this.r,0)):this.g(this.A,l))}b||this.g(this.X)}catch(p){try{this.g(this.A,p)}catch(m){B(this,m)}}return this.a(this.k)},Q.prototype.Q=function(a,b,c,d,e,h,l,p,m,z,s){if(this.m)return this.m;try{if(this.q=false,b=this.a(this.d).length,c=this.a(this.f).length,d=this.j,this.c[this.L]&&H(this,this.a(this.L)),e=this.a(this.h),0<e.length&&R(this,this.d,J(e.length,2).concat(e),this.R),h=this.a(this.F)&255,h-=this.a(this.d).length+4,l=this.a(this.f),4<l.length&&(h-=l.length+3),0<h&&R(this,this.d,J(h,2).concat(C(h)),this.S),4<l.length&&R(this,this.d,J(l.length,2).concat(l),this.T),p=[3].concat(this.a(this.d)),window.btoa?(z=window.btoa(String.fromCharCode.apply(null,p)),m=z=z.replace(/\\+/g,"-").replace(/\\//g,"_").replace(/=/g,"")):m=k,m)m="!"+m;else for(m="",e=0;e<p.length;e++)s=p[e][this.J](16),1==s.length&&(s="0"+s),m+=s;a=m,this.j=d,this.q=true,this.a(this.d).length=b,this.a(this.f).length=c}catch(v){B(this,v),a=this.m}return a};try{window.addEventListener("unload",function(){},false)}catch(S){}x("botguard.bg",Q),x("botguard.bg.prototype.invoke",Q.prototype.ha);')})()</script>
  <script type="text/javascript">
  document.bg = new botguard.bg('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');
  </script>
<script>
  function gaia_parseFragment() {
  var hash = location.hash;
  var params = {};
  if (!hash) {
  return params;
  }
  var paramStrs = decodeURIComponent(hash.substring(1)).split('&');
  for (var i = 0; i < paramStrs.length; i++) {
      var param = paramStrs[i].split('=');
      params[param[0]] = param[1];
    }
    return params;
  }

  function gaia_prefillEmail() {
    var form = null;
    if (document.getElementById) {
      form = document.getElementById('gaia_loginform');
    }

    if (form && form.Email &&
        (form.Email.value == null || form.Email.value == '')
        && (form.Email.type != 'hidden')) {
      hashParams = gaia_parseFragment();
      if (hashParams['Email'] && hashParams['Email'] != '') {
        form.Email.value = hashParams['Email'];
      }
    }
  }


  try {
    gaia_prefillEmail();
  } catch (e) {
  }

</script>
<script>
  function gaia_setFocus() {
  var form = null;
  var isFocusableField = function(inputElement) {
  if (!inputElement) {
  return false;
  }
  if (inputElement.type != 'hidden' && inputElement.focus &&
  inputElement.style.display != 'none') {
  return true;
  }
  return false;
  };
  var isFocusableErrorField = function(inputElement) {
  if (!inputElement) {
  return false;
  }
  var hasError = inputElement.className.indexOf('form-error') > -1;
  if (hasError && isFocusableField(inputElement)) {
  return true;
  }
  return false;
  };
  var isFocusableEmptyField = function(inputElement) {
  if (!inputElement) {
  return false;
  }
  var isEmpty = inputElement.value == null || inputElement.value == '';
  if (isEmpty && isFocusableField(inputElement)) {
  return true;
  }
  return false;
  };
  if (document.getElementById) {
  form = document.getElementById('gaia_loginform');
  }
  if (form) {
  var userAgent = navigator.userAgent.toLowerCase();
  var formFields = form.getElementsByTagName('input');
  for (var i = 0; i < formFields.length; i++) {
        var currentField = formFields[i];
        if (isFocusableErrorField(currentField)) {
          currentField.focus();

          var currentValue = currentField.value;
          currentField.value = '';
          currentField.value = currentValue;
          return;
        }
      }



        for (var j = 0; j < formFields.length; j++) {
          var currentField = formFields[j];
          if (isFocusableEmptyField(currentField)) {
            currentField.focus();
            return;
          }
        }

    }
  }




</script>

  </body>
</html>
