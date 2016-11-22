# ol3Module_ProcessArea (using openlayers 3)
---
ol3 version : 3.14.2
---
OpenLayers 3 Module
  - Square Area Controller
  - Polygon Area Controller
  - Link Multiple Map (two)

setting value 
  - mode            // square | polygon | select
  - area_value {    
    limit : 8000,  
    area : 0.0,
    area_string : '0 km<sup>2</sup>'
  }                 
  - polygon_style {
    text_font : '0.6em Malgun Gothic',
    text_color : [50, 50, 50, 1],
    fill_color: 'rgba(255, 255, 255, 0.5)',
    stroke_color : '#185E99',
    stroke_width : 2.5,
    title: '처리영역'
  }

Method
  - getInteraction
  - setAreaLimit
  - getAreaLimit
  - getMode
  - changeMode   (select | polygon | square)
  - changeArea (only square)
  - getMBR
  - getPolygonCoords
  - getArea
  - getAreaString
  - setVisiable
  - setDestMapBoolean
  - getGeoJSON 