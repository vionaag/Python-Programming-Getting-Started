# Python-Programming-Getting-Started 

def welcome_assignment_answers(question):
    if question == "Are encoding and encryption the same? - Yes/No":
        return "No"
    elif question == "Is it possible to decrypt a message without a key? - Yes/No":
        return "No"
    elif question == "In Slack, what is the secret passphrase posted in the #lab-python-getting-started channel posted by a TA?":
        return "nyu"  # Replace with the actual passphrase
    elif question == "Is it possible to decode a message without a key? - Yes/No":
        return "Yes"
    elif question == "Is a hashed message supposed to be un-hashed? - Yes/No":
        return "No"
    elif question == "What is the SHA256 hashing value of your NYU email and use the answer in your code - ":
        return "SHA256:M3k5pCfO+056RhRSfO7al0ELhBQcsVSYwwziCDoX084 va2213@nyu.edu"  # Replace with the actual SHA256 hash of your email
    elif question == "Is MD5 a secured hashing algorithm? - Yes/No":
        return "No"
    elif question == "What layer of the TCP/IP model does the protocol DNS belong to? - The answer should be an integer number":
        return "5"  # DNS operates at the Application layer
    elif question == "What layer of the TCP/IP model does the protocol ICMP belong to? - The answer should be an integer number":
        return "3"  # ICMP operates at the Network layer
    else:
        # Handle typos or unrecognized questions
        return "This is not my beautiful wife! This is not my beautiful car! How did I get here?"

# Example usage
if __name__ == "__main__":
    debug_question = "Are encoding and encryption the same? - Yes/No"
    print(welcome_assignment_answers(debug_question))
