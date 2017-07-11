# hdfs-ceph-client

A client for uploading files from GUODA HDFS to iDigBio's Ceph storage.

Usage: hdfs_ceph_client [OPTIONS] PATH

Options:
  -t, --tar  Upload the file as a GZipped TAR Archive (default for most files)

  -c, --cat  Upload the file as a GZipped concatenated file (default for csv)

  --help     Show this message and exit.
