def capitalize_text(text):
  """
  This function takes a string and returns it with the first letter capitalized.
  """
  return text.capitalize()

def main():
  user_input = "hello world, this is a test."
  formatted_text = capitalize_text(user_input)
  print(f"Original: {user_input}")
  print(f"Formatted: {formatted_text}")

if __name__ == "__main__":
  main()
