# Hello-world

    @GetMapping("getproductById/{id}")
    public ResponseEntity<String> getproductById(@PathVariable("id")String id){
    return ResponseEntity.ok(id);
}
