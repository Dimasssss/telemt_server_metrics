# Server Metrics 2026-03-06 05:03:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 24140.7 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183535
telemt_connections_bad_total 15986
telemt_handshake_timeouts_total 3148
telemt_upstream_connect_attempt_total 25453
telemt_upstream_connect_success_total 25244
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 25244
telemt_upstream_connect_attempts_per_request{bucket="2"} 99
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9754
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 263
telemt_me_reconnect_attempts_total 9240
telemt_me_reconnect_success_total 9206
telemt_me_reader_eof_total 9528
telemt_me_idle_close_by_peer_total 9528
telemt_me_route_drop_no_conn_total 54415
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 548
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 374
telemt_desync_frames_bucket_total{bucket="1_2"} 154
telemt_desync_frames_bucket_total{bucket="3_10"} 196
telemt_desync_frames_bucket_total{bucket="gt_10"} 198
telemt_pool_swap_total 3
telemt_pool_force_close_total 153
telemt_me_writer_removed_unexpected_total 9529
telemt_me_writer_restored_same_endpoint_total 9200
telemt_me_writer_removed_unexpected_minus_restored_total 329
telemt_user_connections_total{user="hello"} 155970
telemt_user_connections_current{user="hello"} 748
telemt_user_octets_from_client{user="hello"} 3500284444 (3.26 GB)
telemt_user_octets_to_client{user="hello"} 60298575876 (56.16 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 24136.3 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68081
telemt_connections_bad_total 124
telemt_handshake_timeouts_total 968
telemt_upstream_connect_attempt_total 23540
telemt_upstream_connect_success_total 23538
telemt_upstream_connect_attempts_per_request{bucket="1"} 23538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10132
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 286
telemt_me_reconnect_attempts_total 6747
telemt_me_reconnect_success_total 6726
telemt_me_reader_eof_total 6876
telemt_me_idle_close_by_peer_total 6876
telemt_me_route_drop_no_conn_total 20277
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 104
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 271
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 178
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 7
telemt_pool_force_close_total 125
telemt_pool_stale_pick_total 1038
telemt_me_writer_removed_unexpected_total 6877
telemt_me_writer_restored_same_endpoint_total 6720
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 65716
telemt_user_connections_current{user="hello"} 284
telemt_user_octets_from_client{user="hello"} 628453432 (599.34 MB)
telemt_user_octets_to_client{user="hello"} 17473553164 (16.27 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 24133.8 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117696
telemt_connections_bad_total 1385
telemt_handshake_timeouts_total 2661
telemt_upstream_connect_attempt_total 23343
telemt_upstream_connect_success_total 23160
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 23160
telemt_upstream_connect_attempts_per_request{bucket="2"} 82
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9210
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 282
telemt_me_reconnect_attempts_total 7292
telemt_me_reconnect_success_total 7265
telemt_me_reader_eof_total 7585
telemt_me_idle_close_by_peer_total 7585
telemt_me_route_drop_no_conn_total 33722
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 101
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 228
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 157
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 67
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 7590
telemt_me_writer_restored_same_endpoint_total 7257
telemt_me_writer_removed_unexpected_minus_restored_total 333
telemt_user_connections_total{user="hello"} 110118
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 1062344176 (1013.13 MB)
telemt_user_octets_to_client{user="hello"} 36815446040 (34.29 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 24130.4 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95909
telemt_connections_bad_total 5090
telemt_handshake_timeouts_total 5458
telemt_upstream_connect_attempt_total 16466
telemt_upstream_connect_success_total 16409
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 16409
telemt_upstream_connect_attempts_per_request{bucket="2"} 28
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6732
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 179
telemt_me_reconnect_attempts_total 3175
telemt_me_reconnect_success_total 3149
telemt_me_reader_eof_total 3257
telemt_me_idle_close_by_peer_total 3257
telemt_me_route_drop_no_conn_total 32905
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 99
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 255
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 165
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 122
telemt_pool_swap_total 8
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 3257
telemt_me_writer_restored_same_endpoint_total 3142
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 80816
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 1459468748 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 31156113336 (29.02 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 24129.3 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109867
telemt_connections_bad_total 1014
telemt_handshake_timeouts_total 640
telemt_upstream_connect_attempt_total 16413
telemt_upstream_connect_success_total 16374
telemt_upstream_connect_attempts_per_request{bucket="1"} 16374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6607
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 224
telemt_me_reconnect_attempts_total 2843
telemt_me_reconnect_success_total 2830
telemt_me_reader_eof_total 2930
telemt_me_idle_close_by_peer_total 2929
telemt_me_route_drop_no_conn_total 37645
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 103
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 153
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 8
telemt_pool_force_close_total 155
telemt_me_writer_removed_unexpected_total 2934
telemt_me_writer_restored_same_endpoint_total 2823
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 106352
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 23543293076 (21.93 GB)
telemt_user_octets_to_client{user="hello"} 62595807744 (58.30 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 65
```