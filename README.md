./bin/op-node \
    # Omitting all above parameters
    # Add the following 2 lines:
    # Set the timestamp for Fjord and Granite hardfork
    --override.fjord=1730106000 \
    --override.granite=1730106000
