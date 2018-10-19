# PETS-ANNOTATION-CONVERSION
PETS-ANNOTATION-CONVERSION

# validate XSD for XML files
xlint --noout --schema  pets_det.xsd PETS2009-S2L1.xml

# Convert XML to YAML file
xml2yaml --schema pets_det.xsd --xml PETS2009-S2L1-c1-det.xml -o PETS2009-S2L1-c1-det.yml
