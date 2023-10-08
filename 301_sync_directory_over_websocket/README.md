# Synchronize Directory over WebSocket

Create a command-line tool to facilitate directory synchronization over a WebSocket connection.

# Instructions

```bash
# Receiver process
sync-directory --port 8080 --output-dir ~/Downloads/output_dir

# Sender process
sync-directory --from ~/Downloads/input_dir --to ws://localhost:8080
```

Once the sender command is completed, the receiver process should exit automatically, and the contents of `input_dir` will be found under `output_dir`.

# Minimum Requirements

1. Implement the "sync" semantic:
   a. If a file exists in the sender's directory but not in the receiver's directory, the file should be copied.
   b. If a file doesn't exist in the sender's directory but does exist in the receiver's directory, the file should be removed.
2. Directory syncing should be performed recursively.

# Good to Have

### Additional Features

We do not require any additional features. If you have extra time, we recommend focusing on polishing the minimum requirements. However, if you can't resist the temptation, feel free to go ahead and surprise us.

# Deliverables

Instructions on how to download the code and run it locally.
