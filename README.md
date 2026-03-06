# Server Metrics 2026-03-06 22:16:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 14895.9 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250315
telemt_connections_bad_total 2218
telemt_handshake_timeouts_total 9075
telemt_upstream_connect_attempt_total 23539
telemt_upstream_connect_success_total 23359
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 23428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15559
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 49
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 1050
telemt_me_reconnect_attempts_total 7084
telemt_me_reconnect_success_total 7048
telemt_me_reader_eof_total 9229
telemt_me_idle_close_by_peer_total 9229
telemt_me_route_drop_no_conn_total 95594
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 125
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 813
telemt_desync_full_logged_total 239
telemt_desync_suppressed_total 574
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 325
telemt_desync_frames_bucket_total{bucket="gt_10"} 251
telemt_pool_swap_total 5
telemt_pool_force_close_total 320
telemt_pool_stale_pick_total 166
telemt_me_writer_removed_unexpected_total 9337
telemt_me_writer_restored_same_endpoint_total 7042
telemt_me_writer_removed_unexpected_minus_restored_total 2295
telemt_user_connections_total{user="hello"} 225325
telemt_user_connections_current{user="hello"} 414
telemt_user_octets_from_client{user="hello"} 3363799584 (3.13 GB)
telemt_user_octets_to_client{user="hello"} 87853229468 (81.82 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 14896.0 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100305
telemt_connections_bad_total 96
telemt_handshake_timeouts_total 8078
telemt_upstream_connect_attempt_total 29219
telemt_upstream_connect_success_total 29218
telemt_upstream_connect_attempts_per_request{bucket="1"} 29218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 484
telemt_me_reconnect_attempts_total 10071
telemt_me_reconnect_success_total 10058
telemt_me_reader_eof_total 14123
telemt_me_idle_close_by_peer_total 14120
telemt_me_route_drop_no_conn_total 36350
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 128
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 644
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 298
telemt_desync_frames_bucket_total{bucket="gt_10"} 241
telemt_pool_swap_total 6
telemt_pool_force_close_total 254
telemt_pool_stale_pick_total 36
telemt_me_writer_removed_unexpected_total 14123
telemt_me_writer_restored_same_endpoint_total 10056
telemt_me_writer_removed_unexpected_minus_restored_total 4067
telemt_user_connections_total{user="hello"} 86724
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 1328039140 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 27409865204 (25.53 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 14895.9 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193186
telemt_connections_bad_total 661
telemt_handshake_timeouts_total 3188
telemt_upstream_connect_attempt_total 23176
telemt_upstream_connect_success_total 23026
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 23069
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13129
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1052
telemt_me_reconnect_attempts_total 6647
telemt_me_reconnect_success_total 6616
telemt_me_reader_eof_total 8828
telemt_me_idle_close_by_peer_total 8825
telemt_me_route_drop_no_conn_total 73252
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 125
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 862
telemt_desync_full_logged_total 212
telemt_desync_suppressed_total 650
telemt_desync_frames_bucket_total{bucket="1_2"} 165
telemt_desync_frames_bucket_total{bucket="3_10"} 345
telemt_desync_frames_bucket_total{bucket="gt_10"} 352
telemt_pool_swap_total 7
telemt_pool_force_close_total 253
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 8933
telemt_me_writer_restored_same_endpoint_total 6609
telemt_me_writer_removed_unexpected_minus_restored_total 2324
telemt_user_connections_total{user="hello"} 178963
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 11993853540 (11.17 GB)
telemt_user_octets_to_client{user="hello"} 53803715028 (50.11 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 14896.2 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192645
telemt_connections_bad_total 53369
telemt_handshake_timeouts_total 14740
telemt_upstream_connect_attempt_total 24867
telemt_upstream_connect_success_total 24795
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 24819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13887
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 476
telemt_me_reconnect_attempts_total 8005
telemt_me_reconnect_success_total 7987
telemt_me_reader_eof_total 10718
telemt_me_idle_close_by_peer_total 10717
telemt_me_route_drop_no_conn_total 49111
telemt_me_single_endpoint_shadow_rotate_total 126
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 164
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 7
telemt_pool_force_close_total 271
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 10723
telemt_me_writer_restored_same_endpoint_total 7982
telemt_me_writer_removed_unexpected_minus_restored_total 2741
telemt_user_connections_total{user="hello"} 121196
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 1594530372 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 36881412648 (34.35 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 14894.7 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165196
telemt_connections_bad_total 458
telemt_handshake_timeouts_total 1190
telemt_upstream_connect_attempt_total 22849
telemt_upstream_connect_success_total 22720
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 22739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13431
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 798
telemt_me_reconnect_attempts_total 6943
telemt_me_reconnect_success_total 6914
telemt_me_reader_eof_total 9372
telemt_me_idle_close_by_peer_total 9371
telemt_me_route_drop_no_conn_total 58163
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 122
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 730
telemt_desync_full_logged_total 181
telemt_desync_suppressed_total 549
telemt_desync_frames_bucket_total{bucket="1_2"} 259
telemt_desync_frames_bucket_total{bucket="3_10"} 234
telemt_desync_frames_bucket_total{bucket="gt_10"} 237
telemt_pool_swap_total 7
telemt_pool_force_close_total 295
telemt_pool_stale_pick_total 203
telemt_me_writer_removed_unexpected_total 9435
telemt_me_writer_restored_same_endpoint_total 6912
telemt_me_writer_removed_unexpected_minus_restored_total 2523
telemt_user_connections_total{user="hello"} 151425
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 9437210484 (8.79 GB)
telemt_user_octets_to_client{user="hello"} 51014327436 (47.51 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 28
```