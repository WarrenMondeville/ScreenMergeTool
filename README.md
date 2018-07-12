# ScreenMergeTool

## master
<?xml version="1.0" encoding="UTF-8"?>
<node type="master" name="Master Node" id="0" nodes="3">
	<server ip="localhost" port="25000"/>	
	<screen stereo="false" eye="">
		<pa x="-8" y="-5" z="0" />
		<pb x="8" y="-5"  z="0" />
		<pc x="-8" y="5" z="0" />
		<pe x="0"  y="0"  z="5" />
	</screen>
</node>

##slave 1
<?xml version="1.0" encoding="UTF-8"?>
<node type="slave" name="Slave Node 1" id="1" nodes="3">
	<server ip="localhost" port="25000"/>
	<screen stereo="false" eye="">
		<pa x="-24" y="-5" z="0" />
		<pb x="-8" y="-5"  z="0" />
		<pc x="-24" y="5" z="0" />
		<pe x="0"  y="0"  z="5" />
	</screen>
</node>
##slave 2
<?xml version="1.0" encoding="UTF-8"?>
<node type="slave" name="Slave Node 2" id="2" nodes="3">
	<server ip="localhost" port="25000"/>	
	<screen stereo="false" eye="">
		<pa x="8" y="-5" z="0" />
		<pb x="8" y="-5"  z="16" />
		<pc x="8" y="5" z="0" />
		<pe x="0"  y="0"  z="5" />
	</screen>
</node>

