# Server Metrics 2026-03-04 07:05:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 35718.0 (9h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 365450
telemt_connections_bad_total 6003
telemt_handshake_timeouts_total 5891
telemt_upstream_connect_attempt_total 22990
telemt_upstream_connect_success_total 22881
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 22881
telemt_upstream_connect_attempts_per_request{bucket="2"} 49
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9872
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 4660
telemt_me_reconnect_success_total 4635
telemt_me_reader_eof_total 4744
telemt_me_idle_close_by_peer_total 4744
telemt_me_route_drop_no_conn_total 123024
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 143
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 756
telemt_desync_full_logged_total 286
telemt_desync_suppressed_total 470
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 264
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 8
telemt_pool_force_close_total 300
telemt_me_writer_removed_unexpected_total 4744
telemt_me_writer_restored_same_endpoint_total 4615
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 309425
telemt_user_connections_current{user="hello"} 850
telemt_user_octets_from_client{user="hello"} 3493344280 (3.25 GB)
telemt_user_octets_to_client{user="hello"} 95292186280 (88.75 GB)
telemt_user_unique_ips_current{user="hello"} 99
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 35714.7 (9h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160834
telemt_connections_bad_total 1235
telemt_handshake_timeouts_total 22754
telemt_upstream_connect_attempt_total 73946
telemt_upstream_connect_success_total 72870
telemt_upstream_connect_fail_total 500
telemt_upstream_connect_attempts_per_request{bucket="1"} 72864
telemt_upstream_connect_attempts_per_request{bucket="2"} 506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23532
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 500
telemt_me_keepalive_timeout_total 1164
telemt_me_reconnect_attempts_total 43431
telemt_me_reconnect_success_total 43357
telemt_me_reader_eof_total 44433
telemt_me_idle_close_by_peer_total 44432
telemt_me_route_drop_no_conn_total 57086
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 303
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 199
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 158
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 44513
telemt_me_writer_restored_same_endpoint_total 43332
telemt_me_writer_removed_unexpected_minus_restored_total 1181
telemt_user_connections_total{user="hello"} 110146
telemt_user_connections_current{user="hello"} 292
telemt_user_octets_from_client{user="hello"} 1053157232 (1004.37 MB)
telemt_user_octets_to_client{user="hello"} 44679330352 (41.61 GB)
telemt_user_unique_ips_current{user="hello"} 31
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 35713.5 (9h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 317144
telemt_connections_bad_total 101223
telemt_handshake_timeouts_total 9354
telemt_upstream_connect_attempt_total 51559
telemt_upstream_connect_success_total 51243
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 51242
telemt_upstream_connect_attempts_per_request{bucket="2"} 150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21578
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_keepalive_timeout_total 681
telemt_me_reconnect_attempts_total 22508
telemt_me_reconnect_success_total 22449
telemt_me_reader_eof_total 23681
telemt_me_idle_close_by_peer_total 23678
telemt_me_route_drop_no_conn_total 85722
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 152
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 483
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 303
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 180
telemt_desync_frames_bucket_total{bucket="gt_10"} 175
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 23692
telemt_me_writer_restored_same_endpoint_total 22428
telemt_me_writer_removed_unexpected_minus_restored_total 1264
telemt_user_connections_total{user="hello"} 197700
telemt_user_connections_current{user="hello"} 469
telemt_user_octets_from_client{user="hello"} 1763196224 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 67313130744 (62.69 GB)
telemt_user_unique_ips_current{user="hello"} 59
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 35712.4 (9h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180379
telemt_connections_bad_total 14250
telemt_handshake_timeouts_total 6205
telemt_upstream_connect_attempt_total 27357
telemt_upstream_connect_success_total 27242
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 27242
telemt_upstream_connect_attempts_per_request{bucket="2"} 56
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10341
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 298
telemt_me_reconnect_attempts_total 6004
telemt_me_reconnect_success_total 5992
telemt_me_reader_eof_total 6108
telemt_me_idle_close_by_peer_total 6108
telemt_me_route_drop_no_conn_total 52441
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 149
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 10
telemt_pool_force_close_total 232
telemt_me_writer_removed_unexpected_total 6108
telemt_me_writer_restored_same_endpoint_total 5971
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 141444
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 1404929868 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 51493243316 (47.96 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 35711.2 (9h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 321445
telemt_connections_bad_total 6420
telemt_handshake_timeouts_total 128836
telemt_upstream_connect_attempt_total 49808
telemt_upstream_connect_success_total 49471
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 49471
telemt_upstream_connect_attempts_per_request{bucket="2"} 157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19764
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 674
telemt_me_reconnect_attempts_total 22872
telemt_me_reconnect_success_total 22856
telemt_me_reader_eof_total 24080
telemt_me_idle_close_by_peer_total 24079
telemt_me_route_drop_no_conn_total 83994
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 152
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 229
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 117
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 24093
telemt_me_writer_restored_same_endpoint_total 22831
telemt_me_writer_removed_unexpected_minus_restored_total 1262
telemt_user_connections_total{user="hello"} 180235
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 2389141692 (2.23 GB)
telemt_user_octets_to_client{user="hello"} 40457803060 (37.68 GB)
telemt_user_unique_ips_current{user="hello"} 51
```