# Server Metrics 2026-03-04 04:21:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 25874.6 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172883
telemt_connections_bad_total 1618
telemt_handshake_timeouts_total 3009
telemt_upstream_connect_attempt_total 18870
telemt_upstream_connect_success_total 18787
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 18787
telemt_upstream_connect_attempts_per_request{bucket="2"} 37
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8154
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 204
telemt_me_reconnect_attempts_total 4326
telemt_me_reconnect_success_total 4310
telemt_me_reader_eof_total 4413
telemt_me_idle_close_by_peer_total 4413
telemt_me_route_drop_no_conn_total 57562
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 106
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 446
telemt_desync_full_logged_total 155
telemt_desync_suppressed_total 291
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 171
telemt_pool_swap_total 5
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 4413
telemt_me_writer_restored_same_endpoint_total 4290
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 164271
telemt_user_connections_current{user="hello"} 628
telemt_user_octets_from_client{user="hello"} 1675595476 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 52974368480 (49.34 GB)
telemt_user_unique_ips_current{user="hello"} 52
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 25871.1 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81413
telemt_connections_bad_total 301
telemt_handshake_timeouts_total 20672
telemt_upstream_connect_attempt_total 61616
telemt_upstream_connect_success_total 60982
telemt_upstream_connect_fail_total 301
telemt_upstream_connect_attempts_per_request{bucket="1"} 60976
telemt_upstream_connect_attempts_per_request{bucket="2"} 307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19368
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 301
telemt_me_keepalive_timeout_total 951
telemt_me_reconnect_attempts_total 38501
telemt_me_reconnect_success_total 38474
telemt_me_reader_eof_total 39452
telemt_me_idle_close_by_peer_total 39451
telemt_me_route_drop_no_conn_total 25565
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 190
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 112
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 102
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 39513
telemt_me_writer_restored_same_endpoint_total 38453
telemt_me_writer_removed_unexpected_minus_restored_total 1060
telemt_user_connections_total{user="hello"} 59186
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 558932272 (533.04 MB)
telemt_user_octets_to_client{user="hello"} 27659585036 (25.76 GB)
telemt_user_unique_ips_current{user="hello"} 30
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 25870.0 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185273
telemt_connections_bad_total 67861
telemt_handshake_timeouts_total 4181
telemt_upstream_connect_attempt_total 34088
telemt_upstream_connect_success_total 33863
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 33863
telemt_upstream_connect_attempts_per_request{bucket="2"} 104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13858
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 453
telemt_me_reconnect_attempts_total 13906
telemt_me_reconnect_success_total 13872
telemt_me_reader_eof_total 14610
telemt_me_idle_close_by_peer_total 14607
telemt_me_route_drop_no_conn_total 37065
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 110
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 301
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 194
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 109
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 14615
telemt_me_writer_restored_same_endpoint_total 13851
telemt_me_writer_removed_unexpected_minus_restored_total 764
telemt_user_connections_total{user="hello"} 109542
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 702000300 (669.48 MB)
telemt_user_octets_to_client{user="hello"} 28201611000 (26.26 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 25868.9 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91682
telemt_connections_bad_total 4079
telemt_handshake_timeouts_total 925
telemt_upstream_connect_attempt_total 17673
telemt_upstream_connect_success_total 17596
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 17596
telemt_upstream_connect_attempts_per_request{bucket="2"} 38
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6733
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 185
telemt_me_reconnect_attempts_total 2812
telemt_me_reconnect_success_total 2813
telemt_me_reader_eof_total 2835
telemt_me_idle_close_by_peer_total 2835
telemt_me_route_drop_no_conn_total 30014
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 107
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 106
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 8
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 2835
telemt_me_writer_restored_same_endpoint_total 2792
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 82667
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 705337920 (672.66 MB)
telemt_user_octets_to_client{user="hello"} 27928209428 (26.01 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 25867.5 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203755
telemt_connections_bad_total 3608
telemt_handshake_timeouts_total 93273
telemt_upstream_connect_attempt_total 38363
telemt_upstream_connect_success_total 38094
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 38094
telemt_upstream_connect_attempts_per_request{bucket="2"} 125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15657
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 538
telemt_me_reconnect_attempts_total 18927
telemt_me_reconnect_success_total 18919
telemt_me_reader_eof_total 20025
telemt_me_idle_close_by_peer_total 20024
telemt_me_route_drop_no_conn_total 49233
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 110
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 134
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 67
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 20036
telemt_me_writer_restored_same_endpoint_total 18895
telemt_me_writer_removed_unexpected_minus_restored_total 1141
telemt_user_connections_total{user="hello"} 103190
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 658971960 (628.44 MB)
telemt_user_octets_to_client{user="hello"} 23289279028 (21.69 GB)
telemt_user_unique_ips_current{user="hello"} 16
```