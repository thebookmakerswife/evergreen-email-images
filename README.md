# evergreen-email-images

Public image host for Evergreen marketing emails.

Every file here is servable at a predictable URL:

    https://raw.githubusercontent.com/thebookmakerswife/evergreen-email-images/main/<filename>

Workflow: drop a new image in, it gets optimized (resize ~1200px, compress,
HEIC/PNG -> JPG, clean lowercase-hyphen name), commit, push. The raw URL is
then derivable from the filename with no manual URL-grabbing.
