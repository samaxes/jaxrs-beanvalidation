# JAX-RS Bean Validation I18N

JAX-RS and Bean Validation integration and error message internationalization.  
Companion code to go along with the blog post http://www.samaxes.com/2013/01/beanvalidation-with-jaxrs-in-javaee6/.

## Configuration

Rename the resource property file to have the file [ValidationMessages.properties](src/main/resources/ValidationMessages.properties) to map to the `Locale` as returned by `Locale.getDefault()`.
