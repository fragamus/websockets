web: echo "oooooooooooooooooooooooooooooooooooooooooooooo";lein with-profile uberjar deps :tree;jar tf target/uberjar.jar;echo "oooooooooooooooooooooooooooooooooooooooooooooo";java $JVM_OPTS -Dconfig=config/prod.edn -cp target/uberjar.jar clojure.main -m app.core
