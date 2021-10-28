# Django Snippets Pro

Django Snippets Pro provides django support for Sulime Text.

| Snippets     | Description                                                                      |
|--------------|----------------------------------------------------------------------------------|
| [Imports]()  | Snippets For Imports                   				                          |
| [Models]()   | Snippets For Models, Model Fields      				                          |
| [Forms]()    | Snippets For Forms, Form Fields   		   				                          |
| [Views]()    | Snippets For Views(Views, GenericViews, AdminViews & Extra snippets for methods) |
| [Files]()    | Snippets For File Templates (urls, forms, cutomtags)	   						  |
| [Urls]()     | Snippets For Urls (FBV path, CVB path, path as Include)   						  |
| [html]()     | Snippets For HMTL files                                 						  |


## Installation

Using [Package Control](https://packagecontrol.io/installation):

- Open the Command Pallete (`ctrl+shift+P` or `cmd+shift+P`).
- Type “Install Package” and hit return.
- Type “Django Sinppets Pro” and hit return.

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
| msmallauto   | SmallAuto		| ``models.SmallAutoField()``          |
| mtext        | Text	        | ``models.TextField()``                  |
| mtime        | Time			| ``models.TimeField()``                  |
| murl         | URL			| ``models.URLField()``                   |
| musstate     | USState		| ``models.USStateField()``               |
| muuid        | MUUID			| ``models.UUIDField()``                  |
| mxml         | XML			| ``models.XMLField()``                   |
| fk           | Foreignkey		| ``models.ForeignKey()``                 |
| m2m          | ManyToMany		| ``models.ManyToManyField()``            |
| o2o          | OneToOne		| ``models.OneToOneField()``              |


## Django Snippets For Forms

| Abbreviation |  Description                  |
|--------------|-------------------------------|
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


## Django Snippet For File Templates

| Abbreviation   |  Description                  |
|----------------|-------------------------------|
| urlfile        |  Url File Template            |
| formfile       |  Forms File Tempalte          |
| customtagsfile |  Custom Tags File Template    |


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
| \_\_str\_\_        |  \_\_str\_\_    		         	 |
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


#### Urls Extra Snippets

| Abbreviation   |  Description                  |
|----------------|-------------------------------|
| path     	     |  FBV path                     |
| cpath     	 |  CBV path          		     |
| ipath     	 |  path as Include           	 |


## Django Snippets For HTML Files

| Abbreviation   | Description                                            |
|----------------|--------------------------------------------------------|
| autoescape     | ``{% autoescape %} {% autoescape %}``                  |
| block          | ``{% block %} {% endblock %}``                         |
| blocktrans     | ``{% blocktrans %} {% endblocktrans %}``               |
| blocktrans     | ``{% blocktrans with as %} {% endblocktrans %}``       |
| comment        | ``{% comment %} {% endcomment %}``                     |
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
| inc            | ``{% include %}``                                      |
| include        | ``{% include %}``                                      |
| load           | ``{% load %}``                                         |
| now            | ``{% now "" %}``                                       |
| regroup        | ``{% regroup by as %}``                                |
| spaceless      | ``{% spaceless %} {% endspaceless %}``                 |
| ssi            | ``{% ssi %}``                                          |
| static         | ``{% static %}``                                       |
| templatetag    | ``{% templatetag %}``                                  |
| trans          | ``{% trans %}``                                        |
| url            | ``{% url %}``                                          |
| verbatim       | ``{% verbatim %} {% endverbatim %}``                   |
| vv             | ``{{   }}``             						          |
| widthratio     | ``{% widthratio %}``                                   |
| with           | ``{% with as %} {% endwith %}``                        |
| extrahead      | ``{% block extrahead %} {% endblock extrahead %}``     |
| extrasyle      | ``{% block extrastyle %} {% endblock extrastyle %}``   |
| extrajslibs    | ``{% block extrajslibs %} {% endblock extrajslibs %}`` |
| extrascript    | ``{% block extrascript %} {% endblock extrascript %}`` |
