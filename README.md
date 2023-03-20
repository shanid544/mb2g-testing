# Apache Maven: Beginner to Guru

This respository contains code examples for the online course [Apache Maven: Beginner to Guru.](https://www.udemy.com/draft/2043700/?couponCode=GITHUB_REPO)

## Testing Java with Maven Examples


<build>
        <plugins>
            <plugin>
                <groupId>org.apache.maven.plugins</groupId>
                <artifactId>maven-surefire-plugin</artifactId>
                <version>2.22.0</version>
            </plugin>
        </plugins>
</build>

we added above build in in pom bcoz the "maven-surefire-plugin" in the intellij maven is not compatable with Junit5 so we are updating the version of maven-surefire-plugin

without updating the test 0 test will run.
