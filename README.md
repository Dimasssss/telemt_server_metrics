# Server Metrics 2026-03-13 17:28:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 127779.5 (35h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4073334
telemt_connections_bad_total 37522
telemt_handshake_timeouts_total 101002
telemt_upstream_connect_attempt_total 27116
telemt_upstream_connect_success_total 26938
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 27116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_timeout_total 5673
telemt_me_reconnect_attempts_total 28340
telemt_me_reconnect_success_total 18235
telemt_me_reader_eof_total 19588
telemt_me_idle_close_by_peer_total 19587
telemt_me_route_drop_no_conn_total 1513773
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3719669
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14549
telemt_desync_full_logged_total 3862
telemt_desync_suppressed_total 10687
telemt_desync_frames_bucket_total{bucket="1_2"} 3623
telemt_desync_frames_bucket_total{bucket="3_10"} 5513
telemt_desync_frames_bucket_total{bucket="gt_10"} 5413
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 18805
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18222
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 570
telemt_user_connections_total{user="hello"} 3721838
telemt_user_connections_current{user="hello"} 1629
telemt_user_octets_from_client{user="hello"} 52478037744 (48.87 GB)
telemt_user_octets_to_client{user="hello"} 1158824824837 (1.05 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 431
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 27443.4 (7h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 409984
telemt_connections_bad_total 30556
telemt_handshake_timeouts_total 10387
telemt_upstream_connect_attempt_total 7917
telemt_upstream_connect_success_total 7743
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 7917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3155
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_timeout_total 1582
telemt_me_reconnect_attempts_total 8313
telemt_me_reconnect_success_total 4918
telemt_me_reader_eof_total 5211
telemt_me_idle_close_by_peer_total 5210
telemt_me_route_drop_no_conn_total 155600
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 357413
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1255
telemt_desync_full_logged_total 320
telemt_desync_suppressed_total 935
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 595
telemt_desync_frames_bucket_total{bucket="gt_10"} 417
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 5085
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 4910
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 358751
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 3682522391 (3.43 GB)
telemt_user_octets_to_client{user="hello"} 104319628092 (97.16 GB)
telemt_user_msgs_from_client{user="hello"} 4402
telemt_user_msgs_to_client{user="hello"} 9145
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 157400.1 (43h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2979678
telemt_connections_bad_total 28459
telemt_handshake_timeouts_total 199629
telemt_upstream_connect_attempt_total 35141
telemt_upstream_connect_success_total 35131
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 35141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16837
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3401
telemt_me_reconnect_attempts_total 29535
telemt_me_reconnect_success_total 26981
telemt_me_reader_eof_total 28599
telemt_me_idle_close_by_peer_total 28598
telemt_me_route_drop_no_conn_total 1014520
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2459734
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8505
telemt_desync_full_logged_total 2816
telemt_desync_suppressed_total 5689
telemt_desync_frames_bucket_total{bucket="1_2"} 1366
telemt_desync_frames_bucket_total{bucket="3_10"} 3115
telemt_desync_frames_bucket_total{bucket="gt_10"} 4024
telemt_pool_swap_total 147
telemt_me_writer_removed_unexpected_total 27296
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 26940
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 315
telemt_user_connections_total{user="hello"} 2459088
telemt_user_connections_current{user="hello"} 1112
telemt_user_octets_from_client{user="hello"} 40411270196 (37.64 GB)
telemt_user_octets_to_client{user="hello"} 858896703653 (799.91 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 299
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 157400.8 (43h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1922644
telemt_connections_bad_total 18256
telemt_handshake_timeouts_total 178488
telemt_upstream_connect_attempt_total 49008
telemt_upstream_connect_success_total 46670
telemt_upstream_connect_fail_total 2201
telemt_upstream_connect_attempts_per_request{bucket="1"} 48734
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18653
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2200
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11967
telemt_me_reconnect_attempts_total 41976
telemt_me_reconnect_success_total 32993
telemt_me_reader_eof_total 35431
telemt_me_idle_close_by_peer_total 35424
telemt_me_route_drop_no_conn_total 681941
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1584001
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3117
telemt_desync_full_logged_total 1012
telemt_desync_suppressed_total 2105
telemt_desync_frames_bucket_total{bucket="1_2"} 862
telemt_desync_frames_bucket_total{bucket="3_10"} 1283
telemt_desync_frames_bucket_total{bucket="gt_10"} 972
telemt_pool_swap_total 136
telemt_me_writer_removed_unexpected_total 33537
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 32969
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 544
telemt_user_connections_total{user="hello"} 1588692
telemt_user_connections_current{user="hello"} 707
telemt_user_octets_from_client{user="hello"} 24521525093 (22.84 GB)
telemt_user_octets_to_client{user="hello"} 601817683226 (560.49 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 26836.3 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 439168
telemt_connections_bad_total 4535
telemt_handshake_timeouts_total 4541
telemt_upstream_connect_attempt_total 6153
telemt_upstream_connect_success_total 5958
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 6153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3181
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_keepalive_timeout_total 853
telemt_me_reconnect_attempts_total 16310
telemt_me_reconnect_success_total 4599
telemt_me_reader_eof_total 5060
telemt_me_idle_close_by_peer_total 5060
telemt_me_route_drop_no_conn_total 169630
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 410330
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1271
telemt_desync_full_logged_total 405
telemt_desync_suppressed_total 866
telemt_desync_frames_bucket_total{bucket="1_2"} 413
telemt_desync_frames_bucket_total{bucket="3_10"} 509
telemt_desync_frames_bucket_total{bucket="gt_10"} 349
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5001
telemt_me_refill_failed_total 364
telemt_me_writer_restored_same_endpoint_total 4595
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 402
telemt_user_connections_total{user="hello"} 410304
telemt_user_connections_current{user="hello"} 907
telemt_user_octets_from_client{user="hello"} 4715036328 (4.39 GB)
telemt_user_octets_to_client{user="hello"} 129448769152 (120.56 GB)
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 118
```