set(COMPONENT_SRCS. 
                   "wifi.c")
set(COMPONENT_ADD_INCLUDEDIRS ".")
# Embed the server root certificate into the final binary
set(COMPONENT_EMBED_TXTFILES ${IDF_PROJECT_PATH}/server_certs/ca_cert.pem)

register_component()
