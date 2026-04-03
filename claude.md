Python ile docling indir pip install ile sonrasında da 

from docling.document_converter import DocumentConverter

# Change this to a local path or another URL if desired.
# Note: using the default URL requires network access; if offline, provide a
# local file path (e.g., Path("/path/to/file.pdf")).
source = "dxl_reference_manual.pdf"

converter = DocumentConverter()
result = converter.convert(source)

# Print Markdown to stdout.
print(result.document.export_to_markdown())
ile dxl_reference_manual dosyasını oku markdown oluştur. Başka bilgisayarda opencode ile okuyacağım bunu
