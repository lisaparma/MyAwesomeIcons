# AwIcons-react 
React component to easily add Awesome Icons to your project.

You can see all icons [here](https://fontawesome.com/icons?d=gallery&m=free)

## How to use it

### 1. Add this repo as submodule of your project with:
	
~~~~
git add submodule git@github.com:lisaparma/AwIcons-react.git
~~~~

### 2. Use _AwIcon_ functional component in your file in this way:	
~~~~
    <AwIcon
      iconName="angle-left"
      color="#FFFFFF"
      size="12px"
      style={style.icon}
      onClick={this._goTo}
    />
~~~~
You can specify 5 props:
* _iconName_ : [required] take from [here](https://fontawesome.com/icons?d=gallery&m=free)
* _color_ : set icon color without defining rule to do it on your scss file
* _size_ : set icon font'size without defing rule to do it on your scss file
* _style_ : pass className to defining rules on your scss file
* _onClick_ : arrow function 


---
Font Awesome Free 5.12.1 by @fontawesome - https://fontawesome.com
 * License - https://fontawesome.com/license/free (Icons: CC BY 4.0, Fonts: SIL OFL 1.1, Code: MIT License)
