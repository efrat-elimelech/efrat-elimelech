 flavor_list = client_manager.compute.flavors.list()
    print("\nFlavors:")
    for f in flavor_list:
        print("%s" % f)
