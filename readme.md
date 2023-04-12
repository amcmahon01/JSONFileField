## JSON File Field

This a utility package intended for saving data to JSON files.  The key functionality is creating a separate temporary file for every nested array of objects, allowing data to be appended to any object without needing to rewrite everything in a single JSON file.  When all writing is completed, the temporary files are assembled into a single JSON file.  If operations are interrupted, the temporary files can be reassembled after the fact without data loss.  Optionally, files are also formatted to be more human-readable.
