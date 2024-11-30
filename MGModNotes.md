If not specified, default value is 1, no max, no min value

KV = KV + (Boost rate * Nerf)

### NERF: 
apply a multiplier to a KV. x0 bans it entirely

### MIN: 
sets a min value

### MAX: 
sets a max value

### LINK: 
creates a parent-child relationship between KV, such that upgrading the parent always upgrades the child. Then, it bans the child from appearing


Abaddon:

Mist Coil:

Limit

"abaddon_death_coil": {

    "effect_radius": { #This is for the ability after gaining the lvl 25 AOE mist coil talent
        "max": 500    #This is 500%, max of 350*5 = 1750
    }
}

Nerf

"abaddon_death_coil": {

    "target_damage": 0.5
}
