def selection_sort(items):
    	print ("Selection Sort")
    for step in range(len(items)):
        
        location_of_smallest = step
        for location in range(step, len(items)):
            
            if items[location] < items[location_of_smallest]:
                location_of_smallest = location
        
        temporary_item = items[step]
        items[step] = items[location_of_smallest]
        items[location_of_smallest] = temporary_item

items = [13,45,52,4,8,69,,7,25,33,21]
print(items)
selection_sort(items)
print(items)

