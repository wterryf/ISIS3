APPNAME = std2isis

include $(ISISROOT)/make/isismake.tsts

commands:
	$(APPNAME) FROM=$(INPUT)/in.png TO=$(OUTPUT)/out.cub \
	> /dev/null;
	catlab from=$(OUTPUT)/out.cub to=$(OUTPUT)/outLabel.pvl > /dev/null;
