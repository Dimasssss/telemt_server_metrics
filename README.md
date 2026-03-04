# Server Metrics 2026-03-04 06:19:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 32953.8 (9h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279516
telemt_connections_bad_total 3000
telemt_handshake_timeouts_total 5047
telemt_upstream_connect_attempt_total 22026
telemt_upstream_connect_success_total 21925
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 21925
telemt_upstream_connect_attempts_per_request{bucket="2"} 45
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9439
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 228
telemt_me_reconnect_attempts_total 4641
telemt_me_reconnect_success_total 4617
telemt_me_reader_eof_total 4725
telemt_me_idle_close_by_peer_total 4725
telemt_me_route_drop_no_conn_total 104764
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 134
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 687
telemt_desync_full_logged_total 258
telemt_desync_suppressed_total 429
telemt_desync_frames_bucket_total{bucket="1_2"} 196
telemt_desync_frames_bucket_total{bucket="3_10"} 244
telemt_desync_frames_bucket_total{bucket="gt_10"} 247
telemt_pool_swap_total 7
telemt_pool_force_close_total 253
telemt_me_writer_removed_unexpected_total 4725
telemt_me_writer_restored_same_endpoint_total 4597
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 260749
telemt_user_connections_current{user="hello"} 771
telemt_user_octets_from_client{user="hello"} 2784950944 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 82804872348 (77.12 GB)
telemt_user_unique_ips_current{user="hello"} 90
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 32950.5 (9h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141881
telemt_connections_bad_total 704
telemt_handshake_timeouts_total 22147
telemt_upstream_connect_attempt_total 71505
telemt_upstream_connect_success_total 70632
telemt_upstream_connect_fail_total 420
telemt_upstream_connect_attempts_per_request{bucket="1"} 70626
telemt_upstream_connect_attempts_per_request{bucket="2"} 426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22953
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 420
telemt_me_keepalive_timeout_total 1043
telemt_me_reconnect_attempts_total 42646
telemt_me_reconnect_success_total 42614
telemt_me_reader_eof_total 43685
telemt_me_idle_close_by_peer_total 43684
telemt_me_route_drop_no_conn_total 45150
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 142
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 255
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 159
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 39
telemt_me_writer_removed_unexpected_total 43746
telemt_me_writer_restored_same_endpoint_total 42593
telemt_me_writer_removed_unexpected_minus_restored_total 1153
telemt_user_connections_total{user="hello"} 92885
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 877109712 (836.48 MB)
telemt_user_octets_to_client{user="hello"} 37988479784 (35.38 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 32949.3 (9h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 277701
telemt_connections_bad_total 94058
telemt_handshake_timeouts_total 6580
telemt_upstream_connect_attempt_total 45420
telemt_upstream_connect_success_total 45137
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 45137
telemt_upstream_connect_attempts_per_request{bucket="2"} 133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18846
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 589
telemt_me_reconnect_attempts_total 19013
telemt_me_reconnect_success_total 18964
telemt_me_reader_eof_total 20000
telemt_me_idle_close_by_peer_total 19997
telemt_me_route_drop_no_conn_total 67106
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 141
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 417
telemt_desync_full_logged_total 155
telemt_desync_suppressed_total 262
telemt_desync_frames_bucket_total{bucket="1_2"} 107
telemt_desync_frames_bucket_total{bucket="3_10"} 158
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 20008
telemt_me_writer_restored_same_endpoint_total 18943
telemt_me_writer_removed_unexpected_minus_restored_total 1065
telemt_user_connections_total{user="hello"} 168852
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 1307784860 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 44791511476 (41.72 GB)
telemt_user_unique_ips_current{user="hello"} 55
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 32948.2 (9h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145374
telemt_connections_bad_total 11752
telemt_handshake_timeouts_total 3348
telemt_upstream_connect_attempt_total 26171
telemt_upstream_connect_success_total 26078
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 26078
telemt_upstream_connect_attempts_per_request{bucket="2"} 46
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9963
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 284
telemt_me_reconnect_attempts_total 5940
telemt_me_reconnect_success_total 5930
telemt_me_reader_eof_total 6043
telemt_me_idle_close_by_peer_total 6043
telemt_me_route_drop_no_conn_total 43697
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 139
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 145
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 81
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 9
telemt_pool_force_close_total 213
telemt_me_writer_removed_unexpected_total 6043
telemt_me_writer_restored_same_endpoint_total 5909
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 122520
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 1167541256 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 44934991580 (41.85 GB)
telemt_user_unique_ips_current{user="hello"} 40
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 32946.8 (9h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 290504
telemt_connections_bad_total 6394
telemt_handshake_timeouts_total 127011
telemt_upstream_connect_attempt_total 46328
telemt_upstream_connect_success_total 46003
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 46003
telemt_upstream_connect_attempts_per_request{bucket="2"} 153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18493
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 632
telemt_me_reconnect_attempts_total 21664
telemt_me_reconnect_success_total 21652
telemt_me_reader_eof_total 22843
telemt_me_idle_close_by_peer_total 22842
telemt_me_route_drop_no_conn_total 69091
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 141
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 202
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 137
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 4
telemt_pool_force_close_total 114
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 22856
telemt_me_writer_restored_same_endpoint_total 21627
telemt_me_writer_removed_unexpected_minus_restored_total 1229
telemt_user_connections_total{user="hello"} 152111
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 2103819440 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 35618994332 (33.17 GB)
telemt_user_unique_ips_current{user="hello"} 43
```