SOURCES += modules/dropbox
SOURCES += modules/urllib3
SOURCES += modules/requests
SOURCES += modules/pkg_resources
SOURCES += modules/six.py
SOURCES += modules/py2typing/typing.py
SOURCES += icon.png
SOURCES += main.py
SOURCES += metadata.xml
SOURCES += settings.ui

ZIP = current.zip

all: $(ZIP)

$(ZIP): $(SOURCES)
	zip -r $@ $^
