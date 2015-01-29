# CMB2 RGBa Colorpicker

A RGBa colorpicker for [CMB2](https://github.com/WebDevStudios/CMB2), I couldn't find one, so I made this plugin, that is all.

Big thanks to [23r9io](https://github.com/23r9i0/wp-color-picker-alpha) for the JS.

## Usage
```
array(
	'name'    => __( 'RGBa Colorpicker', 'cmb2' ),
	'desc'    => __( 'Field description (optional)', 'cmb2' ),
    'id'   => $prefix . 'test_colorpicker',
    'type' => 'rgba_colorpicker',
    'default'  => '#ffffff',
),
```