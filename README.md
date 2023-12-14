# fake-image-classification

To undergo ELA data preprocessing:
=> Follow the structure to create folders for storing ELA images:
   -> ./data/preprocessed_images
      -> ./data/preprocessed_images/training
        -> ./data/preprocessed_images/training/real
        -> ./data/preprocessed_images/training/fake
      -> ./data/preprocessed_images/test
        -> ./data/preprocessed_images/test/real
        -> ./data/preprocessed_images/test/fake
        
=> Uncomment the code "convert_all_to_ela(train_real_path_list, train_fake_path_list, test_real_path_list, test_fake_path_list)"

=> Result stored in train_accs, test_accs, train_losses, test_losses.