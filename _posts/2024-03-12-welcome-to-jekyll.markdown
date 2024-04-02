layout: post
title:  "Crime development in San Francisco within the decade (from 2008 to 2018)"
date:   2024-03-12 10:28:34 +0100
categories: jekyll update
---
<!-- You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %} -->




[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/ -->



<!-- This is my first website. -->

<img src="/images/1.png" alt="Image 1">

<!-- <img src="/images/2.png" alt="Image 2"> -->

<!-- <img src="/images/3.png" alt="Image 3"> -->








<!DOCTYPE HTML>
<html>

<head>
    <meta charset="utf-8">

    <title>Jupyter Notebook</title>
    <link id="favicon" rel="shortcut icon" type="image/x-icon" href="/static/base/images/favicon-notebook.ico?v=eb02bb6f6435d048eba1bf1bd3b3621f8c14f26518dbadd8efd4ee6ee2721caf2367bc0cbc27d2ee2c35bc3b035aad07c6d625422b9445bf301897f493d0edc5">
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <link rel="stylesheet" href="/static/components/jquery-ui/dist/themes/smoothness/jquery-ui.min.css?v=32f9dcde0cd9843f2b66d34c1c9928b59a5d7ef007ba7a6a6a790b3e78f7857a698444d7a716dfaf8fa834c3b3175efd258bbc07cfc4aabb86769b07e5f358c3" type="text/css" />
    <link rel="stylesheet" href="/static/components/jquery-typeahead/dist/jquery.typeahead.min.css?v=5edf53bf6bb9c3b1ddafd8594825a7e2ed621f19423e569c985162742f63911c09eba2c529f8fb47aebf27fafdfe287d563347f58c1126b278189a18871b6a9a" type="text/css" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    


<script type="text/javascript" src="/static/components/MathJax/MathJax.js?config=TeX-AMS-MML_HTMLorMML-full,Safe&delayStartupUntil=configured" charset="utf-8"></script>

<script type="text/javascript">
// MathJax disabled, set as null to distinguish from *missing* MathJax,
// where it will be undefined, and should prompt a dialog later.
window.mathjax_url = "/static/components/MathJax/MathJax.js";
</script>

<link rel="stylesheet" href="/static/components/bootstrap-tour/build/css/bootstrap-tour.min.css?v=95c93e52db61ab29625defe55361384ce6776a7d303b97da5a73fef5ddf8e391a6223599a0b58669476bd71645a4f0022df0517c88b0c05df80ba465e36f5417" type="text/css" />
<link rel="stylesheet" href="/static/components/codemirror/lib/codemirror.css?v=a545ad5e21a51420a7cb40234688eef087a5cf3798f64d7750291a8be0e9c760b8a1c9cbbbdcaa6470f2f385caa59e816f2640f609d29147f4762e27f69709e6">


    <link rel="stylesheet" href="/static/style/style.min.css?v=e1ab1c38b672063a6541baf468c83345cd0f509729783ec9b7ccb64073004f5f056110c82c28aefbf3dbf32e0e040f05b8f0420bc411b669ed3d4f07511812ca" type="text/css"/>
    

<link rel="stylesheet" href="/static/notebook/css/override.css?v=16733f6ba5f2224692fe4e654f3cbb2e3cae82f1df06ca53aa1cb88b147465f16c968c0898e2b0203a7ad3a469f82b959e26bb4b27b790f7f364c4336449b0aa" type="text/css" />
<link rel="stylesheet" href=""  id='kernel-css'                             type="text/css" />


    <link rel="stylesheet" href="/custom/custom.css" type="text/css" />
    <script src="/static/components/es6-promise/promise.min.js?v=bea335d74136a63ae1b5130f5ac9a50c6256a5f435e6e09fef599491a84d834a8b0f011ca3eaaca3b4ab6a2da2d3e1191567a2f171e60da1d10e5b9d52f84184" type="text/javascript" charset="utf-8"></script>
    <script src="/static/components/react/react.production.min.js?v=9a0aaf84a316c8bedd6c2ff7d5b5e0a13f8f84ec02442346cba0b842c6c81a6bf6176e64f3675c2ebf357cb5bb048e0b527bd39377c95681d22468da3d5de735" type="text/javascript"></script>
    <script src="/static/components/react/react-dom.production.min.js?v=6fc58c1c4736868ff84f57bd8b85f2bdb985993a9392718f3b4af4bfa10fb4efba2b4ddd68644bd2a8daf0619a3844944c9c43f8528364a1aa6fc01ec1b8ae84" type="text/javascript"></script>
    <script src="/static/components/create-react-class/index.js?v=894ad57246e682b4cfbe7cd5e408dcd6b38d06af4de4f3425991e2676fdc2ef1732cbd19903104198878ae77de12a1996de3e7da3a467fb226bdda8f4618faec" type="text/javascript"></script>
    <script src="/static/components/requirejs/require.js?v=d37b48bb2137faa0ab98157e240c084dd5b1b5e74911723aa1d1f04c928c2a03dedf922d049e4815f7e5a369faa2e6b6a1000aae958b7953b5cc60411154f593" type="text/javascript" charset="utf-8"></script>
    <script>
      require.config({
          
          urlArgs: "v=20240402095122",
          
          baseUrl: '/static/',
          paths: {
            'auth/js/main': 'auth/js/main.min',
            custom : '/custom',
            nbextensions : '/nbextensions',
            kernelspecs : '/kernelspecs',
            underscore : 'components/underscore/underscore-min',
            backbone : 'components/backbone/backbone-min',
            jed: 'components/jed/jed',
            jquery: 'components/jquery/jquery.min',
            json: 'components/requirejs-plugins/src/json',
            text: 'components/requirejs-text/text',
            bootstrap: 'components/bootstrap/dist/js/bootstrap.min',
            bootstraptour: 'components/bootstrap-tour/build/js/bootstrap-tour.min',
            'jquery-ui': 'components/jquery-ui/dist/jquery-ui.min',
            moment: 'components/moment/min/moment-with-locales',
            codemirror: 'components/codemirror',
            termjs: 'components/xterm.js/xterm',
            typeahead: 'components/jquery-typeahead/dist/jquery.typeahead.min',
          },
          map: { // for backward compatibility
              "*": {
                  "jqueryui": "jquery-ui",
              }
          },
          shim: {
            typeahead: {
              deps: ["jquery"],
              exports: "typeahead"
            },
            underscore: {
              exports: '_'
            },
            backbone: {
              deps: ["underscore", "jquery"],
              exports: "Backbone"
            },
            bootstrap: {
              deps: ["jquery"],
              exports: "bootstrap"
            },
            bootstraptour: {
              deps: ["bootstrap"],
              exports: "Tour"
            },
            "jquery-ui": {
              deps: ["jquery"],
              exports: "$"
            }
          },
          waitSeconds: 30,
      });

      require.config({
          map: {
              '*':{
                'contents': 'services/contents',
              }
          }
      });

      // error-catching custom.js shim.
      define("custom", function (require, exports, module) {
          try {
              var custom = require('custom/custom');
              console.debug('loaded custom.js');
              return custom;
          } catch (e) {
              console.error("error loading custom.js", e);
              return {};
          }
      })

      // error-catching custom-preload.js shim.
      define("custom-preload", function (require, exports, module) {
          try {
              var custom = require('custom/custom-preload');
              console.debug('loaded custom-preload.js');
              return custom;
          } catch (e) {
              console.error("error loading custom-preload.js", e);
              return {};
          }
      })

    document.nbjs_translations = {"domain": "nbjs", "locale_data": {"nbjs": {"": {"domain": "nbjs"}}}};
    document.documentElement.lang = navigator.language.toLowerCase();
    </script>

    
    

</head>

<body class="notebook_app "
 


  
    data-jupyter-api-token="223c2b36a879cf7f54c3f75249097e90fe87d91b5173dfdd"
  
 
data-base-url="/"
data-ws-url=""
data-notebook-name="Exercise_4.ipynb"
data-notebook-path="Exercise_4.ipynb"

dir="ltr">

<noscript>
    <div id='noscript'>
      Jupyter Notebook requires JavaScript.<br>
      Please enable it to proceed. 
  </div>
</noscript>

<div id="header" role="navigation" aria-label="Top Menu">
  <div  id="newsId" style="display: none">
    
    <div class="alert alert-info" role="alert">
      <div style="display: flex">
        <div>
          <span class="label label-warning">UPDATE</span>
          Read <a href="https://jupyter-notebook.readthedocs.io/en/latest/migrate_to_notebook7.html" style="text-decoration: underline;" target="_blank">the migration plan</a> to Notebook 7 to learn about the new features and the actions to take if you are using extensions
          -
          Please note that updating to Notebook 7 might break some of your extensions.
        </div>
        <div style="margin-left: auto;">
          <a href="" onclick="alert('This message will not be shown anymore.'); return false;">
            <button type="button" class="btn btn-default btn-xs" id="dontShowId">
              Don't show anymore
            </button>
          </a>
        </div>
      </div>
    </div>
    
  </div>
  <div id="header-container" class="container">
  <div id="ipython_notebook" class="nav navbar-brand"><a href="/tree?token=223c2b36a879cf7f54c3f75249097e90fe87d91b5173dfdd" title='dashboard'>
      <img src='/static/base/images/logo.png?v=a2a176ee3cee251ffddf5fa21fe8e43727a9e5f87a06f9c91ad7b776d9e9d3d5e0159c16cc188a3965e00375fb4bc336c16067c688f5040c0c2d4bfdb852a9e4' alt='Jupyter Notebook'/>
  </a></div>

  


<span id="save_widget" class="save_widget">
    <span id="notebook_name" class="filename"></span>
    <span class="checkpoint_status"></span>
    <span class="autosave_status"></span>
</span>


  

<span id="kernel_logo_widget">
  
  <img class="current_kernel_logo" alt="Current Kernel Logo" src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"/>
  
</span>


  
  
  
  

    <span id="login_widget">
      
        <button id="logout" class="btn btn-sm navbar-btn">Logout</button>
      
    </span>

  

  
  
  </div>
  <div class="header-bar"></div>

  
<div id="menubar-container" class="container">
<div id="menubar">
    <div id="menus" class="navbar navbar-default" role="navigation">
        <div class="container-fluid">
            <button type="button" class="btn btn-default navbar-btn navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
              <i class="fa fa-bars"></i>
              <span class="navbar-text">Menu</span>
            </button>
            <p id="kernel_indicator" class="navbar-text indicator_area">
              <span class="kernel_indicator_name">Kernel</span>
              <i id="kernel_indicator_icon"></i>
            </p>
            <i id="readonly-indicator" class="navbar-text" title='This notebook is read-only'>
                <span class="fa-stack">
                    <i class="fa fa-save fa-stack-1x"></i>
                    <i class="fa fa-ban fa-stack-2x text-danger"></i>
                </span>
            </i>
            <i id="modal_indicator" class="navbar-text"></i>
            <span id="notification_area"></span>
            <div class="navbar-collapse collapse">
              <ul class="nav navbar-nav">
                <li class="dropdown"><a href="#" class="dropdown-toggle" id="filelink" data-toggle="dropdown" aria-haspopup="true" aria-controls="file_menu">File</a>
                    <ul id="file_menu" class="dropdown-menu" role="menu" aria-labelledby="filelink">
                        <li id="new_notebook" class="menu_focus_highlight dropdown dropdown-submenu" role="none">
                            <a href="#" role="menuitem" aria-haspopup="true" aria-expanded="false" class="dropdown-toggle" data-toggle="dropdown">New Notebook<span class="sr-only">Dropdown</span></a>
                            <ul class="dropdown-menu" id="menu-new-notebook-submenu" role="menu">
                            </ul>
                        </li>
                        <li id="open_notebook" role="none"
                            title="Opens a new window with the Dashboard view">
                            <a href="#" role="menuitem">Open...</a></li>
                        <!-- <hr/> -->
                        <li class="divider" role="none"></li>
                        <li id="copy_notebook" role="none"
                            title="Open a copy of this notebook's contents and start a new kernel">
                            <a href="#" role="menuitem">Make a Copy...</a></li>
                        <li id="save_notebook_as" role="none"
                            title="Save a copy of the notebook's contents and start a new kernel">
                            <a href="#" role="menuitem">Save as...</a></li>
                        <li id="rename_notebook" role="none"><a href="#" role="menuitem">Rename...</a></li>
                        <li id="save_checkpoint" role="none"><a href="#" role="menuitem">Save and Checkpoint</a></li>
                        <!-- <hr/> -->
                        <li class="divider" role="none"></li>
                        <li id="restore_checkpoint" class="menu_focus_highlight dropdown-submenu" role="none"><a href="#" role="menuitem" aria-haspopup="true" aria-expanded="false" class="dropdown-toggle" data-toggle="dropdown">Revert to Checkpoint<span class="sr-only">Dropdown</span></a>
                          <ul class="dropdown-menu">
                            <li><a href="#"></a></li>
                            <li><a href="#"></a></li>
                            <li><a href="#"></a></li>
                            <li><a href="#"></a></li>
                            <li><a href="#"></a></li>
                          </ul>
                        </li>
                        <li class="divider" role="none"></li>
                        <li id="print_preview" role="none"><a href="#" role="menuitem">Print Preview</a></li>
                        <li class="dropdown-submenu menu_focus_highlight" role="none"><a href="#" role="menuitem" aria-haspopup="true" aria-expanded="false" class="dropdown-toggle" data-toggle="dropdown">Download as<span class="sr-only">Dropdown</span></a>
                            <ul id="download_menu" class="dropdown-menu">
                                
                                <li id="download_asciidoc">
                                    <a href="#">AsciiDoc (.asciidoc)</a>
                                </li>
                                
                                <li id="download_html">
                                    <a href="#">HTML (.html)</a>
                                </li>
                                
                                <li id="download_latex">
                                    <a href="#">LaTeX (.tex)</a>
                                </li>
                                
                                <li id="download_markdown">
                                    <a href="#">Markdown (.md)</a>
                                </li>
                                
                                <li id="download_notebook">
                                    <a href="#">Notebook (.ipynb)</a>
                                </li>
                                
                                <li id="download_pdf">
                                    <a href="#">PDF via LaTeX (.pdf)</a>
                                </li>
                                
                                <li id="download_rst">
                                    <a href="#">reST (.rst)</a>
                                </li>
                                
                                <li id="download_script">
                                    <a href="#">Script ()</a>
                                </li>
                                
                                <li id="download_slides">
                                    <a href="#">Reveal.js slides (.slides.html)</a>
                                </li>
                                
                                <li id="download_webpdf">
                                    <a href="#">PDF via HTML (.html)</a>
                                </li>
                                
                            </ul>
                        </li>
                        <li class="dropdown-submenu hidden" role="none"><a href="#" role="menuitem">Deploy as</a>
                            <ul id="deploy_menu" class="dropdown-menu"></ul>
                        </li>
                        <li class="divider" role="none"></li>
                        <li id="trust_notebook" role="none"
                            title="Trust the output of this notebook">
                            <a href="#" role="menuitem">Trust Notebook</a></li>
                        <li class="divider" role="none"></li>
                        <li id="close_and_halt" role="none"
                            title="Shutdown this notebook's kernel, and close this window">
                            <a href="#" role="menuitem">Close and Halt</a></li>
                    </ul>
                </li>

                <li class="dropdown"><a href="#" class="dropdown-toggle" id="editlink" data-toggle="dropdown" aria-haspopup="true" aria-controls="edit_menu">Edit</a>
                    <ul id="edit_menu" class="dropdown-menu" role="menu" aria-labelledby="editlink">
                        <li id="cut_cell" role="none"><a href="#" role="menuitem">Cut Cells</a></li>
                        <li id="copy_cell" role="none"><a href="#" role="menuitem">Copy Cells</a></li>
                        <li id="paste_cell_above" class="disabled" role="none"><a href="#" role="menuitem" aria-disabled="true">Paste Cells Above</a></li>
                        <li id="paste_cell_below" class="disabled" role="none"><a href="#" role="menuitem" aria-disabled="true">Paste Cells Below</a></li>
                        <li id="paste_cell_replace" class="disabled" role="none"><a href="#" role="menuitem" aria-disabled="true">Paste Cells &amp; Replace</a></li>
                        <li id="delete_cell" role="none"><a href="#" role="menuitem">Delete Cells</a></li>
                        <li id="undelete_cell" class="disabled" role="none"><a href="#" role="menuitem" aria-disabled="true">Undo Delete Cells</a></li>
                        <li class="divider" role="none"></li>
                        <li id="split_cell" role="none"><a href="#" role="menuitem">Split Cell</a></li>
                        <li id="merge_cell_above" role="none"><a href="#" role="menuitem">Merge Cell Above</a></li>
                        <li id="merge_cell_below" role="none"><a href="#" role="menuitem">Merge Cell Below</a></li>
                        <li class="divider" role="none"></li>
                        <li id="move_cell_up" role="none"><a href="#" role="menuitem">Move Cell Up</a></li>
                        <li id="move_cell_down" role="none"><a href="#" role="menuitem">Move Cell Down</a></li>
                        <li class="divider" role="none"></li>
                        <li id="edit_nb_metadata" role="none"><a href="#" role="menuitem">Edit Notebook Metadata</a></li>
                        <li class="divider" role="none"></li>
                        <li id="find_and_replace" role="none"><a href="#" role="menuitem"> Find and Replace </a></li>
                        <li class="divider" role="none"></li>
                        <li id="cut_cell_attachments" role="none"><a href="#" role="menuitem">Cut Cell Attachments</a></li>
                        <li id="copy_cell_attachments" role="none"><a href="#" role="menuitem">Copy Cell Attachments</a></li>
                        <li id="paste_cell_attachments"  class="disabled" role="none"><a href="#" role="menuitem" aria-disabled="true">Paste Cell Attachments</a></li>
                        <li class="divider" role="none"></li>
                        <li id="insert_image" class="disabled" role="none"><a href="#" role="menuitem" aria-disabled="true">  Insert Image </a></li>
                    </ul>
                </li>
                <li class="dropdown"><a href="#" class="dropdown-toggle" id="viewlink" data-toggle="dropdown" aria-haspopup="true" aria-controls="view_menu">View</a>
                    <ul id="view_menu" class="dropdown-menu" role="menu" aria-labelledby="viewlink">
                        <li id="toggle_header" role="none"
                            title="Show/Hide the logo and notebook title (above menu bar)">
                            <a href="#" role="menuitem">Toggle Header</a>
                        </li>
                        <li id="toggle_toolbar" role="none"
                            title="Show/Hide the action icons (below menu bar)">
                            <a href="#" role="menuitem">Toggle Toolbar</a>
                        </li>
                        <li id="toggle_line_numbers" role="none"
                            title="Show/Hide line numbers in cells">
                            <a href="#" role="menuitem">Toggle Line Numbers</a>
                        </li>
                        <li id="menu-cell-toolbar" class="menu_focus_highlight dropdown-submenu" role="none">
                            <a href="#" role="menuitem" aria-haspopup="true" aria-expanded="false" class="dropdown-toggle" data-toggle="dropdown">Cell Toolbar</a>
                            <ul class="dropdown-menu" id="menu-cell-toolbar-submenu"></ul>
                        </li>
                    </ul>
                </li>
                <li class="dropdown"><a href="#" class="dropdown-toggle" id="insertlink" data-toggle="dropdown" aria-haspopup="true" aria-controls="insert_menu">Insert</a>
                    <ul id="insert_menu" class="dropdown-menu" role="menu" aria-labelledby="insertlink">
                        <li id="insert_cell_above" role="none"
                            title="Insert an empty Code cell above the currently active cell">
                            <a href="#" role="menuitem">Insert Cell Above</a></li>
                        <li id="insert_cell_below" role="none"
                            title="Insert an empty Code cell below the currently active cell">
                            <a href="#" role="menuitem">Insert Cell Below</a></li>
                    </ul>
                </li>
                <li class="dropdown"><a href="#" class="dropdown-toggle" id="celllink" data-toggle="dropdown" aria-haspopup="true" aria-controls="cell_menu">Cell</a>
                    <ul id="cell_menu" class="dropdown-menu" role="menu" aria-labelledby="celllink">
                        <li id="run_cell" role="none" title="Run this cell, and move cursor to the next one">
                            <a role="menuitem" href="#">Run Cells</a></li>
                        <li id="run_cell_select_below" role="none" title="Run this cell, select below">
                            <a href="#" role="menuitem">Run Cells and Select Below</a></li>
                        <li id="run_cell_insert_below" role="none" title="Run this cell, insert below">
                            <a href="#" role="menuitem">Run Cells and Insert Below</a></li>
                        <li id="run_all_cells" role="none" title="Run all cells in the notebook">
                            <a href="#" role="menuitem">Run All</a></li>
                        <li id="run_all_cells_above" role="none" title="Run all cells above (but not including) this cell">
                            <a href="#" role="menuitem">Run All Above</a></li>
                        <li id="run_all_cells_below" role="none" title="Run this cell and all cells below it">
                            <a href="#" role="menuitem">Run All Below</a></li>
                        <li class="divider" role="none"></li>
                        <li id="change_cell_type" class="menu_focus_highlight dropdown-submenu" role="none"
                            title="All cells in the notebook have a cell type. By default, new cells are created as 'Code' cells">
                            <a href="#" role="menuitem" aria-haspopup="true" aria-expanded="false" class="dropdown-toggle" data-toggle="dropdown">Cell Type</a>
                            <ul class="dropdown-menu" role="menu">
                              <li id="to_code" role="none"
                                  title="Contents will be sent to the kernel for execution, and output will display in the footer of cell">
                                  <a href="#">Code</a></li>
                              <li id="to_markdown"
                                  title="Contents will be rendered as HTML and serve as explanatory text">
                                  <a href="#">Markdown</a></li>
                              <li id="to_raw"
                                  title="Contents will pass through nbconvert unmodified">
                                  <a href="#">Raw NBConvert</a></li>
                            </ul>
                        </li>
                        <li class="divider" role="none"></li>
                        <li id="current_outputs" class="menu_focus_highlight dropdown-submenu" role="none"><a href="#" role="menuitem" aria-haspopup="true" aria-expanded="false" class="dropdown-toggle" data-toggle="dropdown">Current Outputs</a>
                            <ul class="dropdown-menu" role="menu">
                                <li id="toggle_current_output" role="none"
                                    title="Hide/Show the output of the current cell">
                                    <a href="#">Toggle</a>
                                </li>
                                <li id="toggle_current_output_scroll"
                                    title="Scroll the output of the current cell">
                                    <a href="#">Toggle Scrolling</a>
                                </li>
                                <li id="clear_current_output"
                                    title="Clear the output of the current cell">
                                    <a href="#">Clear</a>
                                </li>
                            </ul>
                        </li>
                        <li id="all_outputs" class="menu_focus_highlight dropdown-submenu" role="none"><a href="#" role="menuitem" aria-haspopup="true" aria-expanded="false" class="dropdown-toggle" data-toggle="dropdown">All Output</a>
                            <ul class="dropdown-menu" role="menu">
                                <li id="toggle_all_output" role="none"
                                    title="Hide/Show the output of all cells">
                                    <a href="#">Toggle</a>
                                </li>
                                <li id="toggle_all_output_scroll"
                                    title="Scroll the output of all cells">
                                    <a href="#">Toggle Scrolling</a>
                                </li>
                                <li id="clear_all_output"
                                    title="Clear the output of all cells">
                                    <a href="#">Clear</a>
                                </li>
                            </ul>
                        </li>
                    </ul>
                </li>
                <li class="dropdown"><a href="#" class="dropdown-toggle" data-toggle="dropdown" id="kernellink">Kernel</a>
                    <ul id="kernel_menu" class="dropdown-menu" aria-labelledby="kernellink">
                        <li id="int_kernel"
                            title="Send Keyboard Interrupt (CTRL-C) to the Kernel">
                            <a href="#">Interrupt</a>
                        </li>
                        <li id="restart_kernel"
                            title="Restart the Kernel">
                            <a href="#">Restart</a>
                        </li>
                        <li id="restart_clear_output"
                            title="Restart the Kernel and clear all output">
                            <a href="#">Restart &amp; Clear Output</a>
                        </li>
                        <li id="restart_run_all"
                            title="Restart the Kernel and re-run the notebook">
                            <a href="#">Restart &amp; Run All</a>
                        </li>
                        <li id="reconnect_kernel"
                            title="Reconnect to the Kernel">
                            <a href="#">Reconnect</a>
                        </li>
                        <li id="shutdown_kernel"
                            title="Shutdown the Kernel">
                            <a href="#">Shutdown</a>
                        </li>
                        <li class="divider" role="none"></li>
                        <li id="menu-change-kernel" class="menu_focus_highlight dropdown-submenu" role="menuitem">
                            <a href="#" role="menuitem" aria-haspopup="true" aria-expanded="false" class="dropdown-toggle" data-toggle="dropdown">Change kernel</a>
                            <ul class="dropdown-menu" id="menu-change-kernel-submenu"></ul>
                        </li>
                    </ul>
                </li>
                <li class="dropdown"><a href="#" class="dropdown-toggle" data-toggle="dropdown">Help</a>
                    <ul  id="help_menu" class="dropdown-menu">
                        
                        <li id="notebook_tour" title="A quick tour of the notebook user interface"><a href="#">User Interface Tour</a></li>
                        <li id="keyboard_shortcuts" title="Opens a tooltip with all keyboard shortcuts"><a href="#">Keyboard Shortcuts</a></li>
                        <li id="edit_keyboard_shortcuts" title="Opens a dialog allowing you to edit Keyboard shortcuts"><a href="#">Edit Keyboard Shortcuts</a></li>
                        <li class="divider"></li>
                        

						
                        
                            
                                <li><a rel="noreferrer" href="http://nbviewer.jupyter.org/github/ipython/ipython/blob/3.x/examples/Notebook/Index.ipynb" target="_blank" title="Opens in a new window">
                                
                                    <i class="fa fa-external-link menu-icon pull-right"></i>
                                

                                Notebook Help
                                </a></li>
                            
                                <li><a rel="noreferrer" href="https://help.github.com/articles/markdown-basics/" target="_blank" title="Opens in a new window">
                                
                                    <i class="fa fa-external-link menu-icon pull-right"></i>
                                

                                Markdown
                                </a></li>
                            
                            
                        
                        <li class="divider"></li>
                        <li title="About Jupyter Notebook"><a id="notebook_about" href="#">About</a></li>
                        
                    </ul>
                </li>
              </ul>
            </div>
        </div>
    </div>
</div>

<div id="maintoolbar" class="navbar">
  <div class="toolbar-inner navbar-inner navbar-nobg">
    <div id="maintoolbar-container" class="container"></div>
  </div>
</div>
</div>

<div class="lower-header-bar"></div>

</div>

<div id="site">


<div id="ipython-main-app">
    <div id="notebook_panel">
        <div id="notebook"></div>
        <div id='tooltip' class='ipython_tooltip' style='display:none'></div>
    </div>
</div>



</div>



<div id="pager">
    <div id="pager-contents">
        <div id="pager-container" class="container"></div>
    </div>
    <div id='pager-button-area'></div>
</div>






<script type="text/javascript">
    sys_info = {"notebook_version": "6.5.4", "notebook_path": "C:\\Users\\sinar\\anaconda3\\Lib\\site-packages\\notebook", "commit_source": "", "commit_hash": "", "sys_version": "3.11.5 | packaged by Anaconda, Inc. | (main, Sep 11 2023, 13:26:23) [MSC v.1916 64 bit (AMD64)]", "sys_executable": "C:\\Users\\sinar\\anaconda3\\python.exe", "sys_platform": "win32", "platform": "Windows-10-10.0.22631-SP0", "os_name": "nt", "default_encoding": "utf-8"};
</script>

<script src="/static/components/text-encoding/lib/encoding.js?v=737ac6f9f978afb6348b5914877e7d7136de7465cd4cdf389bad9a6b3ad5ceffbfb23febc75c23378967d7d36f98f5388208e8eb78c80f2bf47e8f8c000481ad" charset="utf-8"></script>

<script src="/static/notebook/js/main.min.js?v=526713cdc6bea74c57b8bfd058ce5212622c7403fee7a9869213c663bfb23372bf6bd6cf3fcd998100c3979f4331738ada2b17e8d5808e689a0f2b12912f1125" type="text/javascript" charset="utf-8"></script>



<script type='text/javascript'>
  function _remove_token_from_url() {
    if (window.location.search.length <= 1) {
      return;
    }
    var search_parameters = window.location.search.slice(1).split('&');
    for (var i = 0; i < search_parameters.length; i++) {
      if (search_parameters[i].split('=')[0] === 'token') {
        // remote token from search parameters
        search_parameters.splice(i, 1);
        var new_search = '';
        if (search_parameters.length) {
          new_search = '?' + search_parameters.join('&');
        }
        var new_url = window.location.origin + 
                      window.location.pathname + 
                      new_search + 
                      window.location.hash;
        window.history.replaceState({}, "", new_url);
        return;
      }
    }
  }
  _remove_token_from_url();
  sys_info = {"notebook_version": "6.5.4", "notebook_path": "C:\\Users\\sinar\\anaconda3\\Lib\\site-packages\\notebook", "commit_source": "", "commit_hash": "", "sys_version": "3.11.5 | packaged by Anaconda, Inc. | (main, Sep 11 2023, 13:26:23) [MSC v.1916 64 bit (AMD64)]", "sys_executable": "C:\\Users\\sinar\\anaconda3\\python.exe", "sys_platform": "win32", "platform": "Windows-10-10.0.22631-SP0", "os_name": "nt", "default_encoding": "utf-8"};
  document.addEventListener('DOMContentLoaded', function () {
    const newsId = document.querySelector('#newsId');
    const dontShowId = document.querySelector('#dontShowId');
    const showNotebookNews = localStorage.getItem('showNotebookNews');
    dontShowId.addEventListener('click', () => {
      localStorage.setItem('showNotebookNews', false);
      newsId.style.display = 'none';
    });
    if (!showNotebookNews) newsId.style.display = 'inline';
  });
</script>
</body>

</html>

















<!-- <!DOCTYPE html> -->
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>Bokeh Plot</title>
    <style>
      html, body {
        box-sizing: border-box;
        display: flow-root;
        height: 100%;
        margin: 0;
        padding: 0;
      }
    </style>
    <script type="text/javascript" src="https://cdn.bokeh.org/bokeh/release/bokeh-3.2.1.min.js"></script>
    <script type="text/javascript">
        Bokeh.set_log_level("info");
    </script>
  </head>
  <body>
    <div id="d39c36f0-4e49-491a-9ce5-e55aae136874" data-root-id="p1188" style="display: contents;"></div>
  
    <script type="application/json" id="p1368">
      {"7c2255fc-1c77-444b-b75b-e9aa07d757c8":{"version":"3.2.1","title":"Bokeh Application","roots":[{"type":"object","name":"Figure","id":"p1188","attributes":{"width":800,"height":400,"x_range":{"type":"object","name":"FactorRange","id":"p1198","attributes":{"factors":["1","2","3","4","5","6","7","8","9","10","11","12","13","14","15","16","17","18","19","20","21","22","23","24"]}},"y_range":{"type":"object","name":"DataRange1d","id":"p1190"},"x_scale":{"type":"object","name":"CategoricalScale","id":"p1199"},"y_scale":{"type":"object","name":"LinearScale","id":"p1200"},"title":{"type":"object","name":"Title","id":"p1191","attributes":{"text":"Hourly Crime Counts"}},"renderers":[{"type":"object","name":"GlyphRenderer","id":"p1218","attributes":{"data_source":{"type":"object","name":"ColumnDataSource","id":"p1185","attributes":{"selected":{"type":"object","name":"Selection","id":"p1186","attributes":{"indices":[],"line_indices":[]}},"selection_policy":{"type":"object","name":"UnionRenderers","id":"p1187"},"data":{"type":"map","entries":[["Hour_of_Day",{"type":"ndarray","array":{"type":"bytes","data":"AAAAAAEAAAACAAAAAwAAAAQAAAAFAAAABgAAAAcAAAAIAAAACQAAAAoAAAALAAAADAAAAA0AAAAOAAAADwAAABAAAAARAAAAEgAAABMAAAAUAAAAFQAAABYAAAAXAAAA"},"shape":[24],"dtype":"int32","order":"little"}],["ASSAULT",{"type":"ndarray","array":{"type":"bytes","data":"5RIAAPIQAABGDwAA7QcAAMcEAAAKBAAATgUAAJEHAABaCwAALAwAAMoNAACQDgAAShIAANMPAADyDwAA1xEAANcRAAAiEgAAlhEAAMYRAABuEQAA6hEAAPoQAAB9EAAA"},"shape":[24],"dtype":"int32","order":"little"}],["BURGLARY",{"type":"ndarray","array":{"type":"bytes","data":"MAcAAPIEAACfBQAA3AUAAEEFAACWBAAAGAQAAMYFAAC1CAAADAgAAHkHAAAmBwAANAkAAAUGAADHBgAA0AcAABEJAAC3CwAA8gsAAIcJAACFCAAARwgAAN4HAABoBwAA"},"shape":[24],"dtype":"int32","order":"little"}],["DISORDERLY CONDUCT",{"type":"ndarray","array":{"type":"bytes","data":"9AAAALMAAACYAAAAVwAAAEYAAAAZAQAALwIAANoBAABcAQAA+AAAAL8AAACpAAAAjwAAALoAAACFAAAAkQAAAIAAAAB4AAAAmQAAAHMAAABoAAAAaAAAAKUAAACpAAAA"},"shape":[24],"dtype":"int32","order":"little"}],["DRIVING UNDER THE INFLUENCE",{"type":"ndarray","array":{"type":"bytes","data":"jwEAAHcBAABDAQAAnQAAADkAAAAjAAAAKQAAABwAAAAbAAAAKwAAABAAAAAdAAAAIQAAACcAAAArAAAAPwAAAGYAAAB1AAAAeQAAAIwAAAC9AAAA2QAAADABAAB4AQAA"},"shape":[24],"dtype":"int32","order":"little"}],["DRUG/NARCOTIC",{"type":"ndarray","array":{"type":"bytes","data":"RgYAALIDAAD/AgAAPAIAAKkBAADyAAAA9wEAAG4EAADMBQAA2AYAAPEGAAAGCAAAUAkAAOIKAADaCgAAcQwAABAOAAD3DgAA/wwAAPoKAAA5CAAA+QYAACsIAABCBwAA"},"shape":[24],"dtype":"int32","order":"little"}],["DRUNKENNESS",{"type":"ndarray","array":{"type":"bytes","data":"jAEAAH0BAABaAQAAhwAAAEcAAAAZAAAALQAAAGMAAABVAAAAagAAAG4AAACdAAAAkAAAAJIAAACjAAAAxgAAANsAAADrAAAACgEAAPcAAAAsAQAANQEAAHUBAAB5AQAA"},"shape":[24],"dtype":"int32","order":"little"}],["LARCENY/THEFT",{"type":"ndarray","array":{"type":"bytes","data":"6SsAAEkcAABcEQAAFwsAAEcHAABgBwAAMAsAANYQAADDHAAAhyMAALotAABRMwAAgT4AAOw3AACiOQAAsT0AABBBAAB8SgAAM1wAAGlXAADZTAAA1D4AAFY7AACuMwAA"},"shape":[24],"dtype":"int32","order":"little"}],["PROSTITUTION",{"type":"ndarray","array":{"type":"bytes","data":"4gIAACECAABYAQAAzwAAAG8AAAA6AAAAMAAAAB0AAAAcAAAAEAAAACAAAABEAAAA1gAAAFEAAACIAAAAgQAAAIYAAACSAAAA6gAAAL0BAAByAQAALQEAACECAADdAgAA"},"shape":[24],"dtype":"int32","order":"little"}],["ROBBERY",{"type":"ndarray","array":{"type":"bytes","data":"IAYAAJkGAACpBgAAIwQAAJwCAAAkAgAA8gEAAM4BAAAnAgAAbwIAANECAAA9AwAA3gMAAAsEAABABAAAfgQAABcFAAAfBQAAfgUAANEFAAB2BgAAiQcAADgHAADwBgAA"},"shape":[24],"dtype":"int32","order":"little"}],["STOLEN PROPERTY",{"type":"ndarray","array":{"type":"bytes","data":"OQEAAO8AAADSAAAApQAAAJAAAAB0AAAAegAAAKwAAADGAAAA4QAAAPsAAAAuAQAAbQEAAIUBAACVAQAAkAEAAL4BAADLAQAA0gEAAIYBAABjAQAATQEAAEQBAAAdAQAA"},"shape":[24],"dtype":"int32","order":"little"}],["TRESPASS",{"type":"ndarray","array":{"type":"bytes","data":"JQEAAN4AAAAKAQAA4AAAAKMAAACXAQAAGAMAAAsDAACgAgAAUAIAABQCAAD9AQAAGgIAAAMCAACxAQAA5QEAAL4BAADFAQAAqwEAAHwBAABtAQAAYgEAAD0BAAA4AQAA"},"shape":[24],"dtype":"int32","order":"little"}],["VANDALISM",{"type":"ndarray","array":{"type":"bytes","data":"Yw0AAGYJAADFCAAAVwYAAFYEAACTAwAAKAQAAEYFAAClBwAAOAcAALgHAAA+BwAAkwkAAKIHAACFCAAAGwoAABYLAAClDgAA3hEAAJkQAAD2DwAA+g8AAPEPAACsDgAA"},"shape":[24],"dtype":"int32","order":"little"}],["VEHICLE THEFT",{"type":"ndarray","array":{"type":"bytes","data":"0wYAAJUEAAB3AwAAQAIAAOcBAADmAQAA5wIAAFMEAABCBgAATQYAAPUFAABaBQAAIQgAAKwFAAC5BgAAJwgAAP8JAAAlDQAA3w8AABUOAAA+DwAAzg0AAPgOAAA4DAAA"},"shape":[24],"dtype":"int32","order":"little"}],["WEAPON LAWS",{"type":"ndarray","array":{"type":"bytes","data":"cwIAAMcBAAB7AQAABgEAAMAAAABVAAAAhQAAAPkAAAAXAQAAbwEAAGkBAACGAQAADQIAABoCAAD5AQAAcwIAAMgCAADKAgAADgMAAO0CAABzAgAAYQIAANUCAAB3AgAA"},"shape":[24],"dtype":"int32","order":"little"}]]}}},"view":{"type":"object","name":"CDSView","id":"p1219","attributes":{"filter":{"type":"object","name":"AllIndices","id":"p1220"}}},"glyph":{"type":"object","name":"VBar","id":"p1215","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"ASSAULT"},"line_color":{"type":"value","value":"#1f77b4"},"fill_color":{"type":"value","value":"#1f77b4"},"hatch_color":{"type":"value","value":"#1f77b4"}}},"nonselection_glyph":{"type":"object","name":"VBar","id":"p1216","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"ASSAULT"},"line_color":{"type":"value","value":"#1f77b4"},"line_alpha":{"type":"value","value":0.1},"fill_color":{"type":"value","value":"#1f77b4"},"fill_alpha":{"type":"value","value":0.1},"hatch_color":{"type":"value","value":"#1f77b4"},"hatch_alpha":{"type":"value","value":0.1}}},"muted_glyph":{"type":"object","name":"VBar","id":"p1217","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"ASSAULT"},"line_color":{"type":"value","value":"#1f77b4"},"line_alpha":{"type":"value","value":0.2},"fill_color":{"type":"value","value":"#1f77b4"},"fill_alpha":{"type":"value","value":0.2},"hatch_color":{"type":"value","value":"#1f77b4"},"hatch_alpha":{"type":"value","value":0.2}}}}},{"type":"object","name":"GlyphRenderer","id":"p1227","attributes":{"data_source":{"id":"p1185"},"view":{"type":"object","name":"CDSView","id":"p1228","attributes":{"filter":{"type":"object","name":"AllIndices","id":"p1229"}}},"glyph":{"type":"object","name":"VBar","id":"p1224","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"BURGLARY"},"line_color":{"type":"value","value":"#aec7e8"},"fill_color":{"type":"value","value":"#aec7e8"},"hatch_color":{"type":"value","value":"#aec7e8"}}},"nonselection_glyph":{"type":"object","name":"VBar","id":"p1225","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"BURGLARY"},"line_color":{"type":"value","value":"#aec7e8"},"line_alpha":{"type":"value","value":0.1},"fill_color":{"type":"value","value":"#aec7e8"},"fill_alpha":{"type":"value","value":0.1},"hatch_color":{"type":"value","value":"#aec7e8"},"hatch_alpha":{"type":"value","value":0.1}}},"muted_glyph":{"type":"object","name":"VBar","id":"p1226","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"BURGLARY"},"line_color":{"type":"value","value":"#aec7e8"},"line_alpha":{"type":"value","value":0.2},"fill_color":{"type":"value","value":"#aec7e8"},"fill_alpha":{"type":"value","value":0.2},"hatch_color":{"type":"value","value":"#aec7e8"},"hatch_alpha":{"type":"value","value":0.2}}}}},{"type":"object","name":"GlyphRenderer","id":"p1236","attributes":{"data_source":{"id":"p1185"},"view":{"type":"object","name":"CDSView","id":"p1237","attributes":{"filter":{"type":"object","name":"AllIndices","id":"p1238"}}},"glyph":{"type":"object","name":"VBar","id":"p1233","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"DISORDERLY CONDUCT"},"line_color":{"type":"value","value":"#ff7f0e"},"fill_color":{"type":"value","value":"#ff7f0e"},"hatch_color":{"type":"value","value":"#ff7f0e"}}},"nonselection_glyph":{"type":"object","name":"VBar","id":"p1234","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"DISORDERLY CONDUCT"},"line_color":{"type":"value","value":"#ff7f0e"},"line_alpha":{"type":"value","value":0.1},"fill_color":{"type":"value","value":"#ff7f0e"},"fill_alpha":{"type":"value","value":0.1},"hatch_color":{"type":"value","value":"#ff7f0e"},"hatch_alpha":{"type":"value","value":0.1}}},"muted_glyph":{"type":"object","name":"VBar","id":"p1235","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"DISORDERLY CONDUCT"},"line_color":{"type":"value","value":"#ff7f0e"},"line_alpha":{"type":"value","value":0.2},"fill_color":{"type":"value","value":"#ff7f0e"},"fill_alpha":{"type":"value","value":0.2},"hatch_color":{"type":"value","value":"#ff7f0e"},"hatch_alpha":{"type":"value","value":0.2}}}}},{"type":"object","name":"GlyphRenderer","id":"p1245","attributes":{"data_source":{"id":"p1185"},"view":{"type":"object","name":"CDSView","id":"p1246","attributes":{"filter":{"type":"object","name":"AllIndices","id":"p1247"}}},"glyph":{"type":"object","name":"VBar","id":"p1242","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"DRIVING UNDER THE INFLUENCE"},"line_color":{"type":"value","value":"#ffbb78"},"fill_color":{"type":"value","value":"#ffbb78"},"hatch_color":{"type":"value","value":"#ffbb78"}}},"nonselection_glyph":{"type":"object","name":"VBar","id":"p1243","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"DRIVING UNDER THE INFLUENCE"},"line_color":{"type":"value","value":"#ffbb78"},"line_alpha":{"type":"value","value":0.1},"fill_color":{"type":"value","value":"#ffbb78"},"fill_alpha":{"type":"value","value":0.1},"hatch_color":{"type":"value","value":"#ffbb78"},"hatch_alpha":{"type":"value","value":0.1}}},"muted_glyph":{"type":"object","name":"VBar","id":"p1244","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"DRIVING UNDER THE INFLUENCE"},"line_color":{"type":"value","value":"#ffbb78"},"line_alpha":{"type":"value","value":0.2},"fill_color":{"type":"value","value":"#ffbb78"},"fill_alpha":{"type":"value","value":0.2},"hatch_color":{"type":"value","value":"#ffbb78"},"hatch_alpha":{"type":"value","value":0.2}}}}},{"type":"object","name":"GlyphRenderer","id":"p1254","attributes":{"data_source":{"id":"p1185"},"view":{"type":"object","name":"CDSView","id":"p1255","attributes":{"filter":{"type":"object","name":"AllIndices","id":"p1256"}}},"glyph":{"type":"object","name":"VBar","id":"p1251","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"DRUG/NARCOTIC"},"line_color":{"type":"value","value":"#2ca02c"},"fill_color":{"type":"value","value":"#2ca02c"},"hatch_color":{"type":"value","value":"#2ca02c"}}},"nonselection_glyph":{"type":"object","name":"VBar","id":"p1252","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"DRUG/NARCOTIC"},"line_color":{"type":"value","value":"#2ca02c"},"line_alpha":{"type":"value","value":0.1},"fill_color":{"type":"value","value":"#2ca02c"},"fill_alpha":{"type":"value","value":0.1},"hatch_color":{"type":"value","value":"#2ca02c"},"hatch_alpha":{"type":"value","value":0.1}}},"muted_glyph":{"type":"object","name":"VBar","id":"p1253","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"DRUG/NARCOTIC"},"line_color":{"type":"value","value":"#2ca02c"},"line_alpha":{"type":"value","value":0.2},"fill_color":{"type":"value","value":"#2ca02c"},"fill_alpha":{"type":"value","value":0.2},"hatch_color":{"type":"value","value":"#2ca02c"},"hatch_alpha":{"type":"value","value":0.2}}}}},{"type":"object","name":"GlyphRenderer","id":"p1263","attributes":{"data_source":{"id":"p1185"},"view":{"type":"object","name":"CDSView","id":"p1264","attributes":{"filter":{"type":"object","name":"AllIndices","id":"p1265"}}},"glyph":{"type":"object","name":"VBar","id":"p1260","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"DRUNKENNESS"},"line_color":{"type":"value","value":"#98df8a"},"fill_color":{"type":"value","value":"#98df8a"},"hatch_color":{"type":"value","value":"#98df8a"}}},"nonselection_glyph":{"type":"object","name":"VBar","id":"p1261","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"DRUNKENNESS"},"line_color":{"type":"value","value":"#98df8a"},"line_alpha":{"type":"value","value":0.1},"fill_color":{"type":"value","value":"#98df8a"},"fill_alpha":{"type":"value","value":0.1},"hatch_color":{"type":"value","value":"#98df8a"},"hatch_alpha":{"type":"value","value":0.1}}},"muted_glyph":{"type":"object","name":"VBar","id":"p1262","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"DRUNKENNESS"},"line_color":{"type":"value","value":"#98df8a"},"line_alpha":{"type":"value","value":0.2},"fill_color":{"type":"value","value":"#98df8a"},"fill_alpha":{"type":"value","value":0.2},"hatch_color":{"type":"value","value":"#98df8a"},"hatch_alpha":{"type":"value","value":0.2}}}}},{"type":"object","name":"GlyphRenderer","id":"p1272","attributes":{"data_source":{"id":"p1185"},"view":{"type":"object","name":"CDSView","id":"p1273","attributes":{"filter":{"type":"object","name":"AllIndices","id":"p1274"}}},"glyph":{"type":"object","name":"VBar","id":"p1269","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"LARCENY/THEFT"},"line_color":{"type":"value","value":"#d62728"},"fill_color":{"type":"value","value":"#d62728"},"hatch_color":{"type":"value","value":"#d62728"}}},"nonselection_glyph":{"type":"object","name":"VBar","id":"p1270","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"LARCENY/THEFT"},"line_color":{"type":"value","value":"#d62728"},"line_alpha":{"type":"value","value":0.1},"fill_color":{"type":"value","value":"#d62728"},"fill_alpha":{"type":"value","value":0.1},"hatch_color":{"type":"value","value":"#d62728"},"hatch_alpha":{"type":"value","value":0.1}}},"muted_glyph":{"type":"object","name":"VBar","id":"p1271","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"LARCENY/THEFT"},"line_color":{"type":"value","value":"#d62728"},"line_alpha":{"type":"value","value":0.2},"fill_color":{"type":"value","value":"#d62728"},"fill_alpha":{"type":"value","value":0.2},"hatch_color":{"type":"value","value":"#d62728"},"hatch_alpha":{"type":"value","value":0.2}}}}},{"type":"object","name":"GlyphRenderer","id":"p1281","attributes":{"data_source":{"id":"p1185"},"view":{"type":"object","name":"CDSView","id":"p1282","attributes":{"filter":{"type":"object","name":"AllIndices","id":"p1283"}}},"glyph":{"type":"object","name":"VBar","id":"p1278","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"PROSTITUTION"},"line_color":{"type":"value","value":"#ff9896"},"fill_color":{"type":"value","value":"#ff9896"},"hatch_color":{"type":"value","value":"#ff9896"}}},"nonselection_glyph":{"type":"object","name":"VBar","id":"p1279","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"PROSTITUTION"},"line_color":{"type":"value","value":"#ff9896"},"line_alpha":{"type":"value","value":0.1},"fill_color":{"type":"value","value":"#ff9896"},"fill_alpha":{"type":"value","value":0.1},"hatch_color":{"type":"value","value":"#ff9896"},"hatch_alpha":{"type":"value","value":0.1}}},"muted_glyph":{"type":"object","name":"VBar","id":"p1280","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"PROSTITUTION"},"line_color":{"type":"value","value":"#ff9896"},"line_alpha":{"type":"value","value":0.2},"fill_color":{"type":"value","value":"#ff9896"},"fill_alpha":{"type":"value","value":0.2},"hatch_color":{"type":"value","value":"#ff9896"},"hatch_alpha":{"type":"value","value":0.2}}}}},{"type":"object","name":"GlyphRenderer","id":"p1290","attributes":{"data_source":{"id":"p1185"},"view":{"type":"object","name":"CDSView","id":"p1291","attributes":{"filter":{"type":"object","name":"AllIndices","id":"p1292"}}},"glyph":{"type":"object","name":"VBar","id":"p1287","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"ROBBERY"},"line_color":{"type":"value","value":"#9467bd"},"fill_color":{"type":"value","value":"#9467bd"},"hatch_color":{"type":"value","value":"#9467bd"}}},"nonselection_glyph":{"type":"object","name":"VBar","id":"p1288","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"ROBBERY"},"line_color":{"type":"value","value":"#9467bd"},"line_alpha":{"type":"value","value":0.1},"fill_color":{"type":"value","value":"#9467bd"},"fill_alpha":{"type":"value","value":0.1},"hatch_color":{"type":"value","value":"#9467bd"},"hatch_alpha":{"type":"value","value":0.1}}},"muted_glyph":{"type":"object","name":"VBar","id":"p1289","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"ROBBERY"},"line_color":{"type":"value","value":"#9467bd"},"line_alpha":{"type":"value","value":0.2},"fill_color":{"type":"value","value":"#9467bd"},"fill_alpha":{"type":"value","value":0.2},"hatch_color":{"type":"value","value":"#9467bd"},"hatch_alpha":{"type":"value","value":0.2}}}}},{"type":"object","name":"GlyphRenderer","id":"p1299","attributes":{"data_source":{"id":"p1185"},"view":{"type":"object","name":"CDSView","id":"p1300","attributes":{"filter":{"type":"object","name":"AllIndices","id":"p1301"}}},"glyph":{"type":"object","name":"VBar","id":"p1296","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"STOLEN PROPERTY"},"line_color":{"type":"value","value":"#c5b0d5"},"fill_color":{"type":"value","value":"#c5b0d5"},"hatch_color":{"type":"value","value":"#c5b0d5"}}},"nonselection_glyph":{"type":"object","name":"VBar","id":"p1297","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"STOLEN PROPERTY"},"line_color":{"type":"value","value":"#c5b0d5"},"line_alpha":{"type":"value","value":0.1},"fill_color":{"type":"value","value":"#c5b0d5"},"fill_alpha":{"type":"value","value":0.1},"hatch_color":{"type":"value","value":"#c5b0d5"},"hatch_alpha":{"type":"value","value":0.1}}},"muted_glyph":{"type":"object","name":"VBar","id":"p1298","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"STOLEN PROPERTY"},"line_color":{"type":"value","value":"#c5b0d5"},"line_alpha":{"type":"value","value":0.2},"fill_color":{"type":"value","value":"#c5b0d5"},"fill_alpha":{"type":"value","value":0.2},"hatch_color":{"type":"value","value":"#c5b0d5"},"hatch_alpha":{"type":"value","value":0.2}}}}},{"type":"object","name":"GlyphRenderer","id":"p1308","attributes":{"data_source":{"id":"p1185"},"view":{"type":"object","name":"CDSView","id":"p1309","attributes":{"filter":{"type":"object","name":"AllIndices","id":"p1310"}}},"glyph":{"type":"object","name":"VBar","id":"p1305","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"TRESPASS"},"line_color":{"type":"value","value":"#8c564b"},"fill_color":{"type":"value","value":"#8c564b"},"hatch_color":{"type":"value","value":"#8c564b"}}},"nonselection_glyph":{"type":"object","name":"VBar","id":"p1306","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"TRESPASS"},"line_color":{"type":"value","value":"#8c564b"},"line_alpha":{"type":"value","value":0.1},"fill_color":{"type":"value","value":"#8c564b"},"fill_alpha":{"type":"value","value":0.1},"hatch_color":{"type":"value","value":"#8c564b"},"hatch_alpha":{"type":"value","value":0.1}}},"muted_glyph":{"type":"object","name":"VBar","id":"p1307","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"TRESPASS"},"line_color":{"type":"value","value":"#8c564b"},"line_alpha":{"type":"value","value":0.2},"fill_color":{"type":"value","value":"#8c564b"},"fill_alpha":{"type":"value","value":0.2},"hatch_color":{"type":"value","value":"#8c564b"},"hatch_alpha":{"type":"value","value":0.2}}}}},{"type":"object","name":"GlyphRenderer","id":"p1317","attributes":{"data_source":{"id":"p1185"},"view":{"type":"object","name":"CDSView","id":"p1318","attributes":{"filter":{"type":"object","name":"AllIndices","id":"p1319"}}},"glyph":{"type":"object","name":"VBar","id":"p1314","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"VANDALISM"},"line_color":{"type":"value","value":"#c49c94"},"fill_color":{"type":"value","value":"#c49c94"},"hatch_color":{"type":"value","value":"#c49c94"}}},"nonselection_glyph":{"type":"object","name":"VBar","id":"p1315","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"VANDALISM"},"line_color":{"type":"value","value":"#c49c94"},"line_alpha":{"type":"value","value":0.1},"fill_color":{"type":"value","value":"#c49c94"},"fill_alpha":{"type":"value","value":0.1},"hatch_color":{"type":"value","value":"#c49c94"},"hatch_alpha":{"type":"value","value":0.1}}},"muted_glyph":{"type":"object","name":"VBar","id":"p1316","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"VANDALISM"},"line_color":{"type":"value","value":"#c49c94"},"line_alpha":{"type":"value","value":0.2},"fill_color":{"type":"value","value":"#c49c94"},"fill_alpha":{"type":"value","value":0.2},"hatch_color":{"type":"value","value":"#c49c94"},"hatch_alpha":{"type":"value","value":0.2}}}}},{"type":"object","name":"GlyphRenderer","id":"p1326","attributes":{"data_source":{"id":"p1185"},"view":{"type":"object","name":"CDSView","id":"p1327","attributes":{"filter":{"type":"object","name":"AllIndices","id":"p1328"}}},"glyph":{"type":"object","name":"VBar","id":"p1323","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"VEHICLE THEFT"},"line_color":{"type":"value","value":"#e377c2"},"fill_color":{"type":"value","value":"#e377c2"},"hatch_color":{"type":"value","value":"#e377c2"}}},"nonselection_glyph":{"type":"object","name":"VBar","id":"p1324","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"VEHICLE THEFT"},"line_color":{"type":"value","value":"#e377c2"},"line_alpha":{"type":"value","value":0.1},"fill_color":{"type":"value","value":"#e377c2"},"fill_alpha":{"type":"value","value":0.1},"hatch_color":{"type":"value","value":"#e377c2"},"hatch_alpha":{"type":"value","value":0.1}}},"muted_glyph":{"type":"object","name":"VBar","id":"p1325","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"VEHICLE THEFT"},"line_color":{"type":"value","value":"#e377c2"},"line_alpha":{"type":"value","value":0.2},"fill_color":{"type":"value","value":"#e377c2"},"fill_alpha":{"type":"value","value":0.2},"hatch_color":{"type":"value","value":"#e377c2"},"hatch_alpha":{"type":"value","value":0.2}}}}},{"type":"object","name":"GlyphRenderer","id":"p1335","attributes":{"data_source":{"id":"p1185"},"view":{"type":"object","name":"CDSView","id":"p1336","attributes":{"filter":{"type":"object","name":"AllIndices","id":"p1337"}}},"glyph":{"type":"object","name":"VBar","id":"p1332","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"WEAPON LAWS"},"line_color":{"type":"value","value":"#f7b6d2"},"fill_color":{"type":"value","value":"#f7b6d2"},"hatch_color":{"type":"value","value":"#f7b6d2"}}},"nonselection_glyph":{"type":"object","name":"VBar","id":"p1333","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"WEAPON LAWS"},"line_color":{"type":"value","value":"#f7b6d2"},"line_alpha":{"type":"value","value":0.1},"fill_color":{"type":"value","value":"#f7b6d2"},"fill_alpha":{"type":"value","value":0.1},"hatch_color":{"type":"value","value":"#f7b6d2"},"hatch_alpha":{"type":"value","value":0.1}}},"muted_glyph":{"type":"object","name":"VBar","id":"p1334","attributes":{"x":{"type":"field","field":"Hour_of_Day"},"width":{"type":"value","value":0.7},"top":{"type":"field","field":"WEAPON LAWS"},"line_color":{"type":"value","value":"#f7b6d2"},"line_alpha":{"type":"value","value":0.2},"fill_color":{"type":"value","value":"#f7b6d2"},"fill_alpha":{"type":"value","value":0.2},"hatch_color":{"type":"value","value":"#f7b6d2"},"hatch_alpha":{"type":"value","value":0.2}}}}}],"toolbar":{"type":"object","name":"Toolbar","id":"p1197","attributes":{"tools":[{"type":"object","name":"HoverTool","id":"p1211","attributes":{"renderers":"auto"}}]}},"toolbar_location":"above","left":[{"type":"object","name":"LinearAxis","id":"p1206","attributes":{"ticker":{"type":"object","name":"BasicTicker","id":"p1207","attributes":{"mantissas":[1,2,5]}},"formatter":{"type":"object","name":"BasicTickFormatter","id":"p1208"},"major_label_policy":{"type":"object","name":"AllLabels","id":"p1209"}}}],"right":[{"type":"object","name":"Legend","id":"p1338","attributes":{"click_policy":"mute","items":[{"type":"object","name":"LegendItem","id":"p1339","attributes":{"label":{"type":"value","value":"ASSAULT"},"renderers":[{"id":"p1218"}]}},{"type":"object","name":"LegendItem","id":"p1340","attributes":{"label":{"type":"value","value":"BURGLARY"},"renderers":[{"id":"p1227"}]}},{"type":"object","name":"LegendItem","id":"p1341","attributes":{"label":{"type":"value","value":"DISORDERLY CONDUCT"},"renderers":[{"id":"p1236"}]}},{"type":"object","name":"LegendItem","id":"p1342","attributes":{"label":{"type":"value","value":"DRIVING UNDER THE INFLUENCE"},"renderers":[{"id":"p1245"}]}},{"type":"object","name":"LegendItem","id":"p1343","attributes":{"label":{"type":"value","value":"DRUG/NARCOTIC"},"renderers":[{"id":"p1254"}]}},{"type":"object","name":"LegendItem","id":"p1344","attributes":{"label":{"type":"value","value":"DRUNKENNESS"},"renderers":[{"id":"p1263"}]}},{"type":"object","name":"LegendItem","id":"p1345","attributes":{"label":{"type":"value","value":"LARCENY/THEFT"},"renderers":[{"id":"p1272"}]}},{"type":"object","name":"LegendItem","id":"p1346","attributes":{"label":{"type":"value","value":"PROSTITUTION"},"renderers":[{"id":"p1281"}]}},{"type":"object","name":"LegendItem","id":"p1347","attributes":{"label":{"type":"value","value":"ROBBERY"},"renderers":[{"id":"p1290"}]}},{"type":"object","name":"LegendItem","id":"p1348","attributes":{"label":{"type":"value","value":"STOLEN PROPERTY"},"renderers":[{"id":"p1299"}]}},{"type":"object","name":"LegendItem","id":"p1349","attributes":{"label":{"type":"value","value":"TRESPASS"},"renderers":[{"id":"p1308"}]}},{"type":"object","name":"LegendItem","id":"p1350","attributes":{"label":{"type":"value","value":"VANDALISM"},"renderers":[{"id":"p1317"}]}},{"type":"object","name":"LegendItem","id":"p1351","attributes":{"label":{"type":"value","value":"VEHICLE THEFT"},"renderers":[{"id":"p1326"}]}},{"type":"object","name":"LegendItem","id":"p1352","attributes":{"label":{"type":"value","value":"WEAPON LAWS"},"renderers":[{"id":"p1335"}]}}]}}],"below":[{"type":"object","name":"CategoricalAxis","id":"p1201","attributes":{"ticker":{"type":"object","name":"CategoricalTicker","id":"p1202"},"formatter":{"type":"object","name":"CategoricalTickFormatter","id":"p1203"},"major_label_policy":{"type":"object","name":"AllLabels","id":"p1204"}}}],"center":[{"type":"object","name":"Grid","id":"p1205","attributes":{"axis":{"id":"p1201"}}},{"type":"object","name":"Grid","id":"p1210","attributes":{"dimension":1,"axis":{"id":"p1206"}}}]}}]}}
    </script>
    <script type="text/javascript">
      (function() {
        const fn = function() {
          Bokeh.safely(function() {
            (function(root) {
              function embed_document(root) {
              const docs_json = document.getElementById('p1368').textContent;
              const render_items = [{"docid":"7c2255fc-1c77-444b-b75b-e9aa07d757c8","roots":{"p1188":"d39c36f0-4e49-491a-9ce5-e55aae136874"},"root_ids":["p1188"]}];
              root.Bokeh.embed.embed_items(docs_json, render_items);
              }
              if (root.Bokeh !== undefined) {
                embed_document(root);
              } else {
                let attempts = 0;
                const timer = setInterval(function(root) {
                  if (root.Bokeh !== undefined) {
                    clearInterval(timer);
                    embed_document(root);
                  } else {
                    attempts++;
                    if (attempts > 100) {
                      clearInterval(timer);
                      console.log("Bokeh: ERROR: Unable to run BokehJS code because BokehJS library is missing");
                    }
                  }
                }, 10, root)
              }
            })(window);
          });
        };
        if (document.readyState != "loading") fn();
        else document.addEventListener("DOMContentLoaded", fn);
      })();
    </script>
  </body>
</html>







<p>
We all see lots of numbers and things happening every day. It can be hard to understand it all. So, we make pictures out of these numbers to help us see what's going on. Let me tell you about three kinds of pictures that do just that.

<!-- First, we've got a picture that's like a calendar. It's full of little boxes for each day. But instead of words, there are colors. These colors change if something special happens. If a lot of something happens, like people buying stuff, the box might be a dark color. If not much happens, the box might be light. This helps us see what days are busy or quiet over many years. It's a way to look back and remember what happened when. -->

Now, let's talk about the second picture. It's a map with red dots. This map is of a city, a place where people crime is happening. Each red dot stands for something that happened there. Where you see lots of red dots close together, that's where a lot of stuff goes on. Maybe that's where most crimes happend those areas, or it's a violent(criminal) part of the city with lots of criminals. This map helps us see where the busy spots are.

<!-- Last, there's a picture with bars. Each bar is for one hour of the day. Some bars are tall; this means in that hour, many things happened. Maybe it's when people are going to work or school. Other bars are short; not much happened then. This might be late at night when most people are home. It's a good way to see when things get busy or quiet in a city. -->

The last one is a Bokeh plot which is like a picture of the city's Crimes. With bars that rise and fall across the hours of the day, it shows us when the streets are full of Crime and when they're quiet and there is no crime happening.


All these pictures are like stories. They don't use words but they tell us a lot. The calendar shows us how things change day by day. The map with dots shows us where things happen. And the Bocken plot shows us when things happen. These pictures make it easier for us to see patterns. We can look at them and understand better what's going on around us. And when we understand, we can make better choices or find out more about our city.
</p>
<!-- C:\Users\sinar\socialdata\SirCna98.github.io\images\1.png -->



Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].
