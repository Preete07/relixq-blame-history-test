import hashlib


def generate_hash(data: str) -> str:
    """Generate an MD5 hash for testing crypto-finding detection."""
    return hashlib.md5(data.encode("utf-8")).hexdigest()


if __name__ == "__main__":
    message = "RelixQ finding attribution test"
    result = generate_hash(message)
    print(f"Generated hash: {result}")
