def capitalize_text(text):
  """
  This function takes a string and returns it with the first letter capitalized.
  """
  return text.capitalize()

def count_words(text):
  """
  This function counts the number of words in a given string.
  """
  words = text.split()
  return len(words)

def main():
  user_input = "hello world, this is a test."
  
  # Capitalize text
  formatted_text = capitalize_text(user_input)
  print(f"Original: {user_input}")
  print(f"Formatted: {formatted_text}")

  # Count words
  word_count = count_words(user_input)
  print(f"Word Count: {word_count}")

if __name__ == "__main__":
  main()
