** NOT IMPLEMENTED

- Lots of methods in the JAX-RS types
    - HttpHeaders
    - RuntimeDelegate
    - ResponseBuilder
    - Response
    - ContainerRequestContext
    - ContainerResponseContext
- Async return types (single/stream)
- SSE
- Async request/response interceptors
- Custom reader/writer
- Reader/Writer interceptors
- Async Reader/Writer and interceptors
- Feature/DynamicFeature
- Header delegates
- Exception mapping
- Content negociation
- HEAD and OPTIONS are not implemented according to spec
- Annotation inheritance
- Params
    - Matrix params (Stef votes this can wait)
    - RESTEasy variants (how?)
- Resource locators
    - Stef votes this can wait
- Context interaction with CDI
    - context types should be injectable and bound to request
- Context
    - UriInfo
    - Application
    - Request
    - SecurityContext
    - Providers
    - ResourceContext
    - Configuration
    - Servlet replacements (RESTEasy has one, for remote IP)
    - Vertx context?
- BeanValidation
- Default readers/writers
    - Jsonb/Jsonp
    - Vertx JSON types
    - Async variants of spec
    - Spec:
        - byte[] All media types (*/*).
        - java.lang.String All media types (*/*).
        - java.io.InputStream All media types (*/*).
        - java.io.Reader All media types (*/*).
        - java.io.File All media types (*/*).
        - javax.activation.DataSource All media types (*/*).
        - javax.xml.transform.Source XML types (text/xml, application/xml and media types of the
        - form application/*+xml).
        - javax.xml.bind.JAXBElement and application-supplied JAXB classes XML types (text/xml and
        - application/xml and media types of the form application/*+xml).
        - MultivaluedMap<String,String> Form content (application/x-www-form-urlencoded).
        - StreamingOutput All media types (*/*), MessageBodyWriter only.
        - java.lang.Boolean, java.lang.Character, java.lang.Number Only