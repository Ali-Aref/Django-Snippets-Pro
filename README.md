# Django Snippets Pro

Django Snippets Pro provides django support for Sulime Text.


## Installation

Standard (using [package-control](https://packagecontrol.io/installation)):

- Open the Command Pallete (`ctrl+shift+P` or `cmd+shift+P`).
- Type “Install Package” and hit return.
- Type “Django Sinppets Pro” and hit return.

Manually (using Git):
For Installing the package manually first make sure you have installed git on your system (specially on windows).
Install package as a single command depending on your platform:
┕─━─┑ OSX:
git clone https://github.com/Ali-Aref/Django-Snippets-Pro.git ~/Library/Application Support/Subime Text 3/Packages
┕─━─┑ Linux:
git clone https://github.com/Ali-Aref/Django-Snippets-Pro.git ~/.config/sublime-text-3/Packages
┕─━─┑ Windows: 
git clone https://github.com/Ali-Aref/Django-Snippets-Pro.git %APPDATA%\Sublime Text 3

Package will provide snippets in following categories.

<!-- 
| snippets       | description                                              |
|--------------- |----------------------------------------------------------|
| [imports]()    | snippets for imports                   				    |
| [models]()     | snippets for models, model fields      				    |
| [forms]()      | snippets for forms, form fields   		   				|
| [views]()      | snippets for views(views, genericviews, adminviews)      |
| [views extra]()| snippets for views(views, genericviews, adminviews)      |     
| [files]()      | snippets for file templates (urls, forms, cutomtags)	   	|
| [urls]()       | snippets for urls (fbv path, cvb path, path as include)  |
| [html files]() | snippets for hmtl files                                 	|
 -->

| snippets       | description                                              |
|--------------- |----------------------------------------------------------|
| [imports](https://github.com/Ali-Aref/Django-Snippets-Pro#django-snippets-for-imports)    | snippets for imports                   				    |
| [models](https://github.com/Ali-Aref/Django-Snippets-Pro#django-snippets-for-models)     | snippets for models, model fields      				    |
| [forms](https://github.com/Ali-Aref/Django-Snippets-Pro#django-snippets-for-forms)      | snippets for forms, form fields   		   				|
| [views](https://github.com/Ali-Aref/Django-Snippets-Pro#django-snippets-for-views)      | snippets for views(views, genericviews, adminviews)      |
| [views extra](https://github.com/Ali-Aref/Django-Snippets-Pro#views-extra-snippets)| snippets for views(views, genericviews, adminviews)      |     
| [files](https://github.com/Ali-Aref/Django-Snippets-Pro#django-snippet-for-file-templates)      | snippets for file templates (urls, forms, cutomtags)	   	|
| [urls](https://github.com/Ali-Aref/Django-Snippets-Pro#django-snippets-for-urls)       | snippets for urls (fbv path, cvb path, path as include)  |
| [html files](https://github.com/Ali-Aref/Django-Snippets-Pro#django-snippets-for-html-files) | snippets for hmtl files                                 	|

<br />

## Django Snippets For Imports

| Abbreviation | Tag            | Description                                        |
|--------------|----------------|----------------------------------------------------|
| idm          | models         | ``from django import models``                      |
| idf          | forms          | ``from django import forms``                       |
| igu          | get_user_model | ``from django.contrib.auth import get_user_model`` |
| igv          | generic view   | ``from django.views import generic``               |
| ijr          | JsonResponse   | ``from django.http import JsonResponse``           |
| ir           | reverse        | ``from django.urls import reverse``                |
| irl          | reverse_lazy   | ``from django.urls import reverse_lazy``           |
| pdb          | pdb	        | ``import pdb; pdb.set_trace()``                    |
| ipdb         | ipdb	        | ``import ipdb; ipdb.set_trace()``                  |
| npdb         | npdb	        | ``from nose.tools import set_trace; set_trace()``  |
| traceback    | traceback	    | ``import traceback; traceback.print_exc();``       |


<br />

## Django Snippet For File Templates

| Abbreviation   |  Description                  |
|----------------|-------------------------------|
| urlfile        |  Url File Template            |
| formfile       |  Forms File Tempalte          |
| customtagsfile |  Custom Tags File Template    |


<br >

## Django Snippets For Urls 

| Abbreviation   |  Description                             |
|----------------|------------------------------------------|
| path     	     |  ``path("", VIEW, name="")``             |
| cpath     	 |  ``path("", VIEW.as_view(), name="")``   |
| ipath     	 |  ``path("", include("", namespace=""))`` |
| reverse     	 |  ``reverse("", args=[], kwargs={})``     |
| lreverse     	 |  ``reverse_lazy("", args=[], kwargs={})``|


<br />

## Django Snippets For Models 

| Abbreviation |  Description                  |
|--------------|-------------------------------|
| model        |  Full model template          |
| smodel       |  Simple model template        |


| Abbreviation | Name           | Tag                                     |
|--------------|----------------|-----------------------------------------|
| mauto        | Auto           | ``models.AutoField()``                  |
| mbauto       | BigAuto        | ``models.BigAutoField()``               |
| mbigint      | BigInteger     | ``models.BigIntegerField()``            |
| mbool        | Boolean        | ``models.BooleanField()``               |
| mchar        | Char           | ``models.CharField()``                  |
| mcoseint     | CSInteger	    | ``models.CommaSeparatedIntegerField()`` |
| mdate        | Date		    | ``models.DateField()``                  |
| mdatetime    | DateTime	    | ``models.DateTimeField()``              |
| mdecimal     | Decimal	    | ``models.DecimalField()``               |
| mduration    | Duration	    | ``models.DurationField()``              |
| memail       | Email	        | ``models.EmailField()``                 |
| mfile        | File    	    | ``models.FileField()``                  |
| mfilepath    | FilePath	    | ``models.FilePathField()``              |
| mfloat       | Float		    | ``models.FloatField()``                 |
| mjson        | JSON		    | ``models.JSONField()``                  |
| mgip         | GIP		    | ``models.GenericIPAddressField()``      |
| mimg         | Image		    | ``models.ImageField()``                 |
| mint         | Integer	    | ``models.IntegerField()``               |
| mip          | IP     	    | ``models.IPAddressField()``             |
| mnullbool    | NullBoolean    | ``models.NullBooleanField()``           |
| mphone       | Phone		    | ``models.PhoneNumberField()``           |
| mposint      | PosInterger    | ``models.PositiveIntegerField()``       |
| mposbigint   | PosBigInterger | ``models.PositiveBigIntegerField``      |
| mpossmallint | SmallPosInteger| ``models.PositiveSmallIntegerField()``  |
| mslug        | Slug    		| ``models.SlugField()``                  |
| msmallint    | SmallInt		| ``models.SmallIntegerFiled()``          |
| msmallauto   | SmallAuto		| ``models.SmallAutoField()``             |
| mtext        | Text	        | ``models.TextField()``                  |
| mtime        | Time			| ``models.TimeField()``                  |
| murl         | URL			| ``models.URLField()``                   |
| musstate     | USState		| ``models.USStateField()``               |
| muuid        | MUUID			| ``models.UUIDField()``                  |
| mxml         | XML			| ``models.XMLField()``                   |
| fk           | Foreignkey		| ``models.ForeignKey()``                 |
| m2m          | ManyToMany		| ``models.ManyToManyField()``            |
| o2o          | OneToOne		| ``models.OneToOneField()``              |


<br />

## Django Snippets For Forms

| Abbreviation |  Description                  |
|--------------|-------------------------------|
| formfile     |  Forms File Template          |
| form         |  Django Form                  |
| modelform    |  Django Model Form            |
| fclean       |  clean_field 	         	   |
| ffclean      |  clean    				 	   |


| Abbreviation | Name            | Description                          |
|--------------|-----------------|--------------------------------------|
| fbool        | Boolean	     | ``forms.BooleanField()``             |
| fchar        | Char		     | ``forms.CharField()``                |
| fchoice      | Choice		     | ``forms.ChoiceField()``              |
| fcombo       | Combo		     | ``forms.ComboField()``               |
| fdate        | Date		     | ``forms.DateField()``                |
| fdatetime    | DateTime	     | ``forms.DateTime()``                 |
| fdecimal     | Decimal	     | ``forms.DecimalField()``             |
| fduration    | Duration	     | ``forms.DurationField()``            |
| femail       | Email		     | ``forms.EmailField()``               |
| ffile        | File		     | ``forms.FileField()``                |
| ffilepath    | FilePath	     | ``forms.FilePathField()``            |
| ffloat       | Float		     | ``forms.FloatField()``               |
| fgip         | GIP		     | ``forms.GenericIPAddressField()``    |
| fimg         | Image  	     | ``forms.ImageField()``               |
| fint         | Integer	     | ``forms.IntegerField()``             |
| fip          | IP 		     | ``forms.IPAddressField()``           |
| fmochoice    | ModelChoice     | ``forms.ModelChoiceField()``         |
| fmomuchoice  | ModelMultiChoice| ``forms.ModelMultipleChoiceField()`` |
| fmuchoice    | MultiChoice     | ``forms.MultipleChoiceField()``      |
| fmuval       | MultiValue	     | ``forms.MultipleValueField()``       |
| fnullbool    | NullBoolean     | ``forms.NullBooleanField()``         |
| fregex       | Regex		     | ``forms.RegexField()``               |
| fslug        | Slug   	     | ``forms.SlugField()``                |
| fsdatetime   | SplitDateTime	 | ``forms.SplitDateTime()``            |
| ftime        | Time			 | ``forms.TimeField()``                |
| ftchoice     | TypedChoice 	 | ``forms.TypedChoiceField()``         |
| ftmuchoice   | TupedMultiChoice| ``forms.TypedMultipleChoiceField()`` |
| furl         | URL		     | ``forms.URLField()``                 |
| fuuid        | UUID		     | ``forms.UUIDField()``                |


<br />

## Django Snippets For Views

| Abbreviation   |  Description                  |
|----------------|-------------------------------|
| view           |  FBV View     		         |
| cview          |  CBV View     		         |
| listview       |  List View    				 |
| formview       |  Form View    				 |
| createview     |  Create View    				 |
| updateview     |  Update View    				 |
| detailview     |  Detail View    				 |
| deleteview     |  Delete View    				 |
| templateview   |  Template View  				 |
| adminview  	 |  Admin View (admins.py)	 	 |
| tabularinline  |  Admin Tabular inline view  	 |
| stackedinline  |  Admin Stacked inline view  	 |


#### Views Extra Snippets

| Abbreviation   |  Description                  |
|----------------|-------------------------------|
| init           |  init  			     	 	 |
| \_\_str\_\_        |  \_\_str\_\_    		   	 |
| dispatch       |  dispatch   		         	 |
| forminvalid    |  form_invalid   			 	 |
| formvalid      |  form_valid    			 	 |
| get            |  get    		     		 	 |
| post           |  post	 				 	 |
| getcontextdata |  get_context_data    	 	 |
| getformkwargs  |  get_form_kwargs  		 	 |
| getinitial     |  get_initial 			 	 |
| getobject      |  get_object				 	 |
| getqueryset    |  get_queryset			 	 |
| getsuccessurl  |  get_success_url			 	 |
| r2r     	     |  render_to_response           |

<br >
<br >

## Django Snippets For HTML Files

| Abbreviation   | Description                                            |
|----------------|--------------------------------------------------------|
| autoescape     | ``{% autoescape %} {% autoescape %}``                  |
| block          | ``{% block %} {% endblock %}``                         |
| blocktrans     | ``{% blocktrans %} {% endblocktrans %}``               |
| blocktrans     | ``{% blocktrans with as %} {% endblocktrans %}``       |
| comment        | ``{% comment %} {% endcomment %}``                     |
| commentd       | ``{% comment "" %} {% endcomment %}``                  |
| csrf           | ``{% csrf_token %}``                                   |
| cycle          | ``{% cycle %}``                                        |
| debug          | ``{% debug %}``                                        |
| extends        | ``{% extends "" %}``                                   |
| filter         | ``{% filter %} {% endfilter %}``                       |
| firstof        | ``{% firstof %}``                                      |
| for            | ``{% for in %} {% endfor %}``                          |
| fore           | ``{% for in %} {% empty %} {% endfor %}``              |
| if             | ``{% if %} {% endif %}``                               |
| elif           | ``{% elif %}``                         			      |
| else           | ``{% else %}``                         			      |
| ifchanged      | ``{% ifchanged %} {% endifchanged %}``                 |
| ife            | ``{% if %} {% else %} {% endif %}``                    |
| ifelse         | ``{% if %} {% else %} {% endif %}``                    |
| ifeq           | ``{% ifequal %} {% endifequal %}``                     |
| ifequal        | ``{% ifequal %} {% endifequal %}``                     |
| ifnotequal     | ``{% ifnotequal %} {% endifnotequal %}``               |
| include        | ``{% include %}``                                      |
| load           | ``{% load %}``                                         |
| now            | ``{% now "" %}``                                       |
| regroup        | ``{% regroup by as %}``                                |
| spaceless      | ``{% spaceless %} {% endspaceless %}``                 |
| ssi            | ``{% ssi %}``                                          |
| static         | ``{% static %}``                                       |
| staticu        | ``{{ STATIC_URL }}``                                   |
| media          | ``{{ MEDIA_URL }}``                                    |
| templatetag    | ``{% templatetag %}``                                  |
| trans          | ``{% trans %}``                                        |
| url            | ``{% url %}``                                          |
| verbatim       | ``{% verbatim %} {% endverbatim %}``                   |
| vv             | ``{{   }}``             						          |
| tag            | ``{%   %}``             						          |
| widthratio     | ``{% widthratio %}``                                   |
| with           | ``{% with as %} {% endwith %}``                        |
| extrahead      | ``{% block extrahead %} {% endblock extrahead %}``     |
| extrasyle      | ``{% block extrastyle %} {% endblock extrastyle %}``   |
| extrajslibs    | ``{% block extrajslibs %} {% endblock extrajslibs %}`` |
| extrascript    | ``{% block extrascript %} {% endblock extrascript %}`` |
