#Slide 3

## Description
Syntax error: (catch (const std::ifstream::failure &oops) // Alt: catch (...) std::cerr << oops.what() <<"\n");

## Possible Fix
catch (const std::ifstream::failure &oops) { // Alt: catch (...) 
    std::cerr << oops.what() << "\n";
}

# Name
Lokaghna Velugu Boreddi

