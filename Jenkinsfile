node {

  stage 'Checkout'

    git checkout

  stage 'Test'

    echo "Running tests..."
    sleep 0.5
    echo "Tests pass"

  stage 'Build'

    echo "Building Docker image..."
    sleep 0.5
    echo "Build complete"

  stage 'Deploy'
    
    for r in use1 usw1 cac1 sae1 euc1 apse1 apse2; do
      echo "Deploying to $r"
      sleep 0.5
      echo "Done"
    done

  stage 'Cleanup'

    echo "Scubba dub dub"

}
