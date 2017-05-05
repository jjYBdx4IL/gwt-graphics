# gwt-graphics

GWT SVG support. Repackaged vaadin gwt-graphics for maven central.

## Usage

Add dependency to pom.xml:

        <dependency>
            <groupId>com.github.jjYBdx4IL.gwt</groupId>
            <artifactId>gwt-graphics</artifactId>
            <version>1.0</version>
        </dependency>

Add dependency to your GWT descriptor .gxt.xml:

    <inherits name='org.vaadin.gwtgraphics.GWTGraphics'/>

For a full example, see [GWT Maven Example](https://github.com/jjYBdx4IL/example-maven-project-setups/tree/master/gwt-example),
in particular [Animation.java](https://github.com/jjYBdx4IL/example-maven-project-setups/blob/master/gwt-example/src/main/java/com/github/jjYBdx4IL/maven/examples/gwt/sandbox/client/rpcdemo/Animation.java).