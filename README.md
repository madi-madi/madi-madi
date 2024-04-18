class DevIsm extends Developer
{
    public String $name = "Ibrahim S. Madi";
    public String $position = "Web Developer Laravel & Vue";

    public function knowledge()
    {
        return collect([
            "Laravel",
            "VUE",
            "NUXTJS",
        ]);
    }

    public function contacts()
    {
        return collect([
            "github" => "https://github.com/madi-madi",
            "gitlab" => "https://gitlab.com/madi-madi2010",
        ]);
    }
    
    public function publications()
    {
        return collect([
            "medium" => "https://medium.com/",
        ]);
    }
}
