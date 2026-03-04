# Server Metrics 2026-03-04 07:21:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 36638.9 (10h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 393132
telemt_connections_bad_total 6106
telemt_handshake_timeouts_total 5910
telemt_upstream_connect_attempt_total 23498
telemt_upstream_connect_success_total 23387
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 23387
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10091
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 248
telemt_me_reconnect_attempts_total 4729
telemt_me_reconnect_success_total 4701
telemt_me_reader_eof_total 4811
telemt_me_idle_close_by_peer_total 4811
telemt_me_route_drop_no_conn_total 129109
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 146
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 758
telemt_desync_full_logged_total 288
telemt_desync_suppressed_total 470
telemt_desync_frames_bucket_total{bucket="1_2"} 224
telemt_desync_frames_bucket_total{bucket="3_10"} 264
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 8
telemt_pool_force_close_total 300
telemt_me_writer_removed_unexpected_total 4811
telemt_me_writer_restored_same_endpoint_total 4681
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 326163
telemt_user_connections_current{user="hello"} 818
telemt_user_octets_from_client{user="hello"} 3780821392 (3.52 GB)
telemt_user_octets_to_client{user="hello"} 99532503432 (92.70 GB)
telemt_user_unique_ips_current{user="hello"} 83
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 36637.1 (10h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167043
telemt_connections_bad_total 1309
telemt_handshake_timeouts_total 23028
telemt_upstream_connect_attempt_total 75299
telemt_upstream_connect_success_total 74195
telemt_upstream_connect_fail_total 514
telemt_upstream_connect_attempts_per_request{bucket="1"} 74189
telemt_upstream_connect_attempts_per_request{bucket="2"} 520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23904
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 514
telemt_me_keepalive_timeout_total 1179
telemt_me_reconnect_attempts_total 44027
telemt_me_reconnect_success_total 43951
telemt_me_reader_eof_total 45039
telemt_me_idle_close_by_peer_total 45038
telemt_me_route_drop_no_conn_total 60695
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 158
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 312
telemt_desync_full_logged_total 108
telemt_desync_suppressed_total 204
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 161
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 45119
telemt_me_writer_restored_same_endpoint_total 43926
telemt_me_writer_removed_unexpected_minus_restored_total 1193
telemt_user_connections_total{user="hello"} 115884
telemt_user_connections_current{user="hello"} 356
telemt_user_octets_from_client{user="hello"} 1233710308 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 46064010612 (42.90 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 36634.9 (10h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331043
telemt_connections_bad_total 103573
telemt_handshake_timeouts_total 9804
telemt_upstream_connect_attempt_total 53851
telemt_upstream_connect_success_total 53529
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 53528
telemt_upstream_connect_attempts_per_request{bucket="2"} 153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22617
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 706
telemt_me_reconnect_attempts_total 23927
telemt_me_reconnect_success_total 23866
telemt_me_reader_eof_total 25167
telemt_me_idle_close_by_peer_total 25164
telemt_me_route_drop_no_conn_total 93896
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 516
telemt_desync_full_logged_total 192
telemt_desync_suppressed_total 324
telemt_desync_frames_bucket_total{bucket="1_2"} 136
telemt_desync_frames_bucket_total{bucket="3_10"} 191
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 25178
telemt_me_writer_restored_same_endpoint_total 23845
telemt_me_writer_removed_unexpected_minus_restored_total 1333
telemt_user_connections_total{user="hello"} 208626
telemt_user_connections_current{user="hello"} 514
telemt_user_octets_from_client{user="hello"} 1874118096 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 73174605560 (68.15 GB)
telemt_user_unique_ips_current{user="hello"} 62
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 36633.8 (10h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189885
telemt_connections_bad_total 15080
telemt_handshake_timeouts_total 7048
telemt_upstream_connect_attempt_total 27931
telemt_upstream_connect_success_total 27812
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 27812
telemt_upstream_connect_attempts_per_request{bucket="2"} 58
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10562
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 306
telemt_me_reconnect_attempts_total 6063
telemt_me_reconnect_success_total 6049
telemt_me_reader_eof_total 6166
telemt_me_idle_close_by_peer_total 6166
telemt_me_route_drop_no_conn_total 59376
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 153
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 10
telemt_pool_force_close_total 232
telemt_me_writer_removed_unexpected_total 6166
telemt_me_writer_restored_same_endpoint_total 6028
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 149128
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 1563318824 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 53739603312 (50.05 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 36632.4 (10h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331205
telemt_connections_bad_total 6421
telemt_handshake_timeouts_total 129337
telemt_upstream_connect_attempt_total 51443
telemt_upstream_connect_success_total 51093
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 51093
telemt_upstream_connect_attempts_per_request{bucket="2"} 162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 692
telemt_me_reconnect_attempts_total 23651
telemt_me_reconnect_success_total 23634
telemt_me_reader_eof_total 24899
telemt_me_idle_close_by_peer_total 24898
telemt_me_route_drop_no_conn_total 89214
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 156
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
telemt_me_writer_removed_unexpected_total 24912
telemt_me_writer_restored_same_endpoint_total 23609
telemt_me_writer_removed_unexpected_minus_restored_total 1303
telemt_user_connections_total{user="hello"} 189154
telemt_user_connections_current{user="hello"} 318
telemt_user_octets_from_client{user="hello"} 2446115060 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 42318111844 (39.41 GB)
telemt_user_unique_ips_current{user="hello"} 38
```