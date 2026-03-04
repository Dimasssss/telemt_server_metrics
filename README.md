# Server Metrics 2026-03-04 04:06:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 24953.2 (6h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164066
telemt_connections_bad_total 1617
telemt_handshake_timeouts_total 2912
telemt_upstream_connect_attempt_total 18393
telemt_upstream_connect_success_total 18318
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 18318
telemt_upstream_connect_attempts_per_request{bucket="2"} 33
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7968
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 199
telemt_me_reconnect_attempts_total 4285
telemt_me_reconnect_success_total 4271
telemt_me_reader_eof_total 4372
telemt_me_idle_close_by_peer_total 4372
telemt_me_route_drop_no_conn_total 54838
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 408
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 265
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 146
telemt_desync_frames_bucket_total{bucket="gt_10"} 154
telemt_pool_swap_total 5
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 4372
telemt_me_writer_restored_same_endpoint_total 4251
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 155855
telemt_user_connections_current{user="hello"} 616
telemt_user_octets_from_client{user="hello"} 1525514016 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 48348099688 (45.03 GB)
telemt_user_unique_ips_current{user="hello"} 69
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 24949.8 (6h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77617
telemt_connections_bad_total 292
telemt_handshake_timeouts_total 20171
telemt_upstream_connect_attempt_total 60989
telemt_upstream_connect_success_total 60366
telemt_upstream_connect_fail_total 295
telemt_upstream_connect_attempts_per_request{bucket="1"} 60360
telemt_upstream_connect_attempts_per_request{bucket="2"} 301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 295
telemt_me_keepalive_timeout_total 945
telemt_me_reconnect_attempts_total 38410
telemt_me_reconnect_success_total 38384
telemt_me_reader_eof_total 39362
telemt_me_idle_close_by_peer_total 39361
telemt_me_route_drop_no_conn_total 24286
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 109
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 189
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 112
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 101
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 39423
telemt_me_writer_restored_same_endpoint_total 38363
telemt_me_writer_removed_unexpected_minus_restored_total 1060
telemt_user_connections_total{user="hello"} 56197
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 458220480 (436.99 MB)
telemt_user_octets_to_client{user="hello"} 26958072500 (25.11 GB)
telemt_user_unique_ips_current{user="hello"} 30
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 24948.6 (6h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175853
telemt_connections_bad_total 63743
telemt_handshake_timeouts_total 4136
telemt_upstream_connect_attempt_total 33428
telemt_upstream_connect_success_total 33209
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 33209
telemt_upstream_connect_attempts_per_request{bucket="2"} 102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13585
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 447
telemt_me_reconnect_attempts_total 13844
telemt_me_reconnect_success_total 13812
telemt_me_reader_eof_total 14547
telemt_me_idle_close_by_peer_total 14544
telemt_me_route_drop_no_conn_total 34940
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 106
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 301
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 194
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 109
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 14552
telemt_me_writer_restored_same_endpoint_total 13791
telemt_me_writer_removed_unexpected_minus_restored_total 761
telemt_user_connections_total{user="hello"} 104371
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 643949516 (614.12 MB)
telemt_user_octets_to_client{user="hello"} 27414806616 (25.53 GB)
telemt_user_unique_ips_current{user="hello"} 30
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 24947.7 (6h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86592
telemt_connections_bad_total 3264
telemt_handshake_timeouts_total 860
telemt_upstream_connect_attempt_total 16968
telemt_upstream_connect_success_total 16891
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 16891
telemt_upstream_connect_attempts_per_request{bucket="2"} 38
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6508
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 177
telemt_me_reconnect_attempts_total 2614
telemt_me_reconnect_success_total 2616
telemt_me_reader_eof_total 2634
telemt_me_idle_close_by_peer_total 2634
telemt_me_route_drop_no_conn_total 28816
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 105
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 102
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 7
telemt_pool_force_close_total 157
telemt_me_writer_removed_unexpected_total 2634
telemt_me_writer_restored_same_endpoint_total 2595
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 78911
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 685207020 (653.46 MB)
telemt_user_octets_to_client{user="hello"} 26925485808 (25.08 GB)
telemt_user_unique_ips_current{user="hello"} 29
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 24946.2 (6h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194659
telemt_connections_bad_total 2896
telemt_handshake_timeouts_total 89066
telemt_upstream_connect_attempt_total 37386
telemt_upstream_connect_success_total 37135
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 37135
telemt_upstream_connect_attempts_per_request{bucket="2"} 117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15284
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 518
telemt_me_reconnect_attempts_total 18679
telemt_me_reconnect_success_total 18671
telemt_me_reader_eof_total 19771
telemt_me_idle_close_by_peer_total 19770
telemt_me_route_drop_no_conn_total 47982
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 107
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 131
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 19782
telemt_me_writer_restored_same_endpoint_total 18647
telemt_me_writer_removed_unexpected_minus_restored_total 1135
telemt_user_connections_total{user="hello"} 99084
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 636807896 (607.31 MB)
telemt_user_octets_to_client{user="hello"} 22586702492 (21.04 GB)
telemt_user_unique_ips_current{user="hello"} 23
```