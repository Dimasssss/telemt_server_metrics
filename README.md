# Server Metrics 2026-03-06 04:07:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 20762.1 (5h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146068
telemt_connections_bad_total 15927
telemt_handshake_timeouts_total 2863
telemt_upstream_connect_attempt_total 22906
telemt_upstream_connect_success_total 22729
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 22729
telemt_upstream_connect_attempts_per_request{bucket="2"} 83
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8902
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 249
telemt_me_reconnect_attempts_total 8672
telemt_me_reconnect_success_total 8644
telemt_me_reader_eof_total 8957
telemt_me_idle_close_by_peer_total 8957
telemt_me_route_drop_no_conn_total 40701
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 353
telemt_desync_full_logged_total 124
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 126
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 3
telemt_pool_force_close_total 153
telemt_me_writer_removed_unexpected_total 8957
telemt_me_writer_restored_same_endpoint_total 8638
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 119576
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 2299837320 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 45305831164 (42.19 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 20757.6 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50526
telemt_connections_bad_total 115
telemt_handshake_timeouts_total 715
telemt_upstream_connect_attempt_total 17989
telemt_upstream_connect_success_total 17987
telemt_upstream_connect_attempts_per_request{bucket="1"} 17987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 216
telemt_me_reconnect_attempts_total 3943
telemt_me_reconnect_success_total 3928
telemt_me_reader_eof_total 3995
telemt_me_idle_close_by_peer_total 3995
telemt_me_route_drop_no_conn_total 15065
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 160
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 3996
telemt_me_writer_restored_same_endpoint_total 3922
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 48794
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 371675012 (354.46 MB)
telemt_user_octets_to_client{user="hello"} 12168838076 (11.33 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 20754.9 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87536
telemt_connections_bad_total 973
telemt_handshake_timeouts_total 1648
telemt_upstream_connect_attempt_total 19531
telemt_upstream_connect_success_total 19369
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 19369
telemt_upstream_connect_attempts_per_request{bucket="2"} 72
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7870
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 236
telemt_me_reconnect_attempts_total 5930
telemt_me_reconnect_success_total 5909
telemt_me_reader_eof_total 6180
telemt_me_idle_close_by_peer_total 6180
telemt_me_route_drop_no_conn_total 24762
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 178
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 6184
telemt_me_writer_restored_same_endpoint_total 5901
telemt_me_writer_removed_unexpected_minus_restored_total 283
telemt_user_connections_total{user="hello"} 82009
telemt_user_connections_current{user="hello"} 356
telemt_user_octets_from_client{user="hello"} 839856964 (800.95 MB)
telemt_user_octets_to_client{user="hello"} 27957035524 (26.04 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 20751.6 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73986
telemt_connections_bad_total 2054
telemt_handshake_timeouts_total 4392
telemt_upstream_connect_attempt_total 14045
telemt_upstream_connect_success_total 13998
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 13998
telemt_upstream_connect_attempts_per_request{bucket="2"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 151
telemt_me_reconnect_attempts_total 2777
telemt_me_reconnect_success_total 2757
telemt_me_reader_eof_total 2861
telemt_me_idle_close_by_peer_total 2861
telemt_me_route_drop_no_conn_total 26446
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 85
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 197
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 7
telemt_pool_force_close_total 148
telemt_me_writer_removed_unexpected_total 2861
telemt_me_writer_restored_same_endpoint_total 2750
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 63649
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 686521396 (654.72 MB)
telemt_user_octets_to_client{user="hello"} 26990789448 (25.14 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 20750.5 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86307
telemt_connections_bad_total 989
telemt_handshake_timeouts_total 557
telemt_upstream_connect_attempt_total 15044
telemt_upstream_connect_success_total 15017
telemt_upstream_connect_attempts_per_request{bucket="1"} 15017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6031
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 186
telemt_me_reconnect_attempts_total 2741
telemt_me_reconnect_success_total 2731
telemt_me_reader_eof_total 2829
telemt_me_idle_close_by_peer_total 2829
telemt_me_route_drop_no_conn_total 28788
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 89
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 87
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 47
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 6
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 2831
telemt_me_writer_restored_same_endpoint_total 2725
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 83335
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 16635092640 (15.49 GB)
telemt_user_octets_to_client{user="hello"} 48619094416 (45.28 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 49
```