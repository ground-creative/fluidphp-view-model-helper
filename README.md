 # FluidPhp View Model Helper

FluidPhp is a framework based on the PhpToolCase library, visit [phptoolcase.com](http://phptoolcase.com) for complete guides and examples.

## Installation

Add the package to your composer.json file, to install the helper.

With fluidphp framework:
```
"require": 
{
	"mnsami/composer-custom-directory-installer": "2.0.*" ,
	"fluidphp/viewmodel-helper": "*"
} ,
"extra": 
{
	"installer-paths": 
	{
		"./vendor/fluidphp/helpers/ViewModel": ["fluidphp/viewmodel-helper"]
	}
}
```
Stand-alone:
```		
"require": 
{
	"fluidphp/viewmodel-helper": "*"
}
```

## Project Info

### Project Home

http://phptoolcase.com

### Requirements

php version 5.4+<br>
	
	Add the following to your composer.json file:
	
	- WITH FLUIDPHP FRAMEWORK:

		"require": 
		{
			"mnsami/composer-custom-directory-installer": "1.0.*",
			"fluidphp/viewmodel-helper": "~1.0"
		} ,
		"extra": 
		{
			"installer-paths": 
			{
				"./vendor/fluidphp/helpers/ViewModel": ["fluidphp/viewmodel-helper"]
			}
		}
		
	- STAND-ALONE:
		
		"require": 
		{
			"fluidphp/viewmodel-helper": "~1.0"
		}