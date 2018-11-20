## about
This Document is a manual for xui modding 
@Maik Laschober <Devidian> 11/2018


### sprites

```xml
<element type="sprite">
	<attribute name="FillDirection" type="enum">
		<value>horizontal</value>
		<value>vertical</value>
		<value>radial90</value>
		<value>radial180</value>
		<value>radial360</value>
	</attribute>
	<attribute name="Flip" type="enum">
		<value>Nothing</value>
		<value>Horizontally</value>
		<value>Vertically</value>
		<value>Both</value>
	</attribute>
	<attribute name="Type" type="enum">
		<value>Simple</value>
		<value>Sliced</value>
		<value>Tiled</value>
		<value>Filled</value>
		<value>Advanced</value>
	</attribute>
	<attribute name="AdvancedType" type="enum">
		<value>Invisible</value>
		<value>Sliced</value>
		<value>Tiled</value>
	</attribute>
	<attribute name="FillCenter" type="boolean"></attribute>
	<attribute name="Fill" type="float"></attribute>
	<attribute name="Color" type="Color32"></attribute>
	<attribute name="SpriteName" type="string"></attribute>
	<attribute name="UIAtlas" type="string"></attribute>
	<attribute name="GlobalOpacityModifier" type="float"></attribute>
</element>

```