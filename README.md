# effective-octo-enigma
not html_path.exists():     raise FileNotFoundError("فایل HTML قبلی پیدا نشد.") code = html_path.read_text(encoding="utf-8") txt_path = Path("/mnt/data/ka_buli_source_code.txt") txt_path.write_text(code, encoding="utf-8") zip_path = Path("/mnt/data/ka_buli_website_files.zip") with zipfile.ZipFile(zip_path, "w", compression=
