# Server Metrics 2026-03-13 20:06:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 137262.0 (38h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4372543
telemt_connections_bad_total 37837
telemt_handshake_timeouts_total 105883
telemt_upstream_connect_attempt_total 28785
telemt_upstream_connect_success_total 28589
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 28785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12684
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_timeout_total 6548
telemt_me_reconnect_attempts_total 29517
telemt_me_reconnect_success_total 19401
telemt_me_reader_eof_total 20820
telemt_me_idle_close_by_peer_total 20819
telemt_me_route_drop_no_conn_total 1644602
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4001144
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15836
telemt_desync_full_logged_total 4219
telemt_desync_suppressed_total 11617
telemt_desync_frames_bucket_total{bucket="1_2"} 3951
telemt_desync_frames_bucket_total{bucket="3_10"} 6032
telemt_desync_frames_bucket_total{bucket="gt_10"} 5853
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 19995
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 19388
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 594
telemt_user_connections_total{user="hello"} 4003306
telemt_user_connections_current{user="hello"} 1265
telemt_user_octets_from_client{user="hello"} 58431729220 (54.42 GB)
telemt_user_octets_to_client{user="hello"} 1263039305953 (1.15 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 362
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 36925.9 (10h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 530079
telemt_connections_bad_total 41083
telemt_handshake_timeouts_total 12039
telemt_upstream_connect_attempt_total 10632
telemt_upstream_connect_success_total 10418
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 10632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4100
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 191
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_keepalive_timeout_total 1872
telemt_me_reconnect_attempts_total 9962
telemt_me_reconnect_success_total 6546
telemt_me_reader_eof_total 6924
telemt_me_idle_close_by_peer_total 6923
telemt_me_route_drop_no_conn_total 197535
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 459642
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1556
telemt_desync_full_logged_total 419
telemt_desync_suppressed_total 1137
telemt_desync_frames_bucket_total{bucket="1_2"} 332
telemt_desync_frames_bucket_total{bucket="3_10"} 688
telemt_desync_frames_bucket_total{bucket="gt_10"} 536
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 6743
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 6538
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 461572
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 4937188637 (4.60 GB)
telemt_user_octets_to_client{user="hello"} 146173187756 (136.13 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 166882.7 (46h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3188754
telemt_connections_bad_total 29309
telemt_handshake_timeouts_total 213790
telemt_upstream_connect_attempt_total 37008
telemt_upstream_connect_success_total 36991
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 37008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17626
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 176
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 10191
telemt_me_reconnect_attempts_total 30923
telemt_me_reconnect_success_total 28354
telemt_me_reader_eof_total 30048
telemt_me_idle_close_by_peer_total 30047
telemt_me_route_drop_no_conn_total 1092013
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2640403
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8762
telemt_desync_full_logged_total 2909
telemt_desync_suppressed_total 5853
telemt_desync_frames_bucket_total{bucket="1_2"} 1443
telemt_desync_frames_bucket_total{bucket="3_10"} 3205
telemt_desync_frames_bucket_total{bucket="gt_10"} 4114
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 28696
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 28313
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 342
telemt_user_connections_total{user="hello"} 2639685
telemt_user_connections_current{user="hello"} 743
telemt_user_octets_from_client{user="hello"} 43588166668 (40.59 GB)
telemt_user_octets_to_client{user="hello"} 929982968269 (866.11 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 166883.1 (46h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2064068
telemt_connections_bad_total 22503
telemt_handshake_timeouts_total 193407
telemt_upstream_connect_attempt_total 52242
telemt_upstream_connect_success_total 49805
telemt_upstream_connect_fail_total 2300
telemt_upstream_connect_attempts_per_request{bucket="1"} 51968
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19642
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2299
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20202
telemt_me_reconnect_attempts_total 43471
telemt_me_reconnect_success_total 34463
telemt_me_reader_eof_total 36998
telemt_me_idle_close_by_peer_total 36991
telemt_me_route_drop_no_conn_total 730128
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1702014
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3674
telemt_desync_full_logged_total 1174
telemt_desync_suppressed_total 2500
telemt_desync_frames_bucket_total{bucket="1_2"} 968
telemt_desync_frames_bucket_total{bucket="3_10"} 1528
telemt_desync_frames_bucket_total{bucket="gt_10"} 1178
telemt_pool_swap_total 146
telemt_me_writer_removed_unexpected_total 35035
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 34439
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 572
telemt_user_connections_total{user="hello"} 1707883
telemt_user_connections_current{user="hello"} 488
telemt_user_octets_from_client{user="hello"} 26262323327 (24.46 GB)
telemt_user_octets_to_client{user="hello"} 641574041094 (597.51 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 36318.7 (10h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 568388
telemt_connections_bad_total 5702
telemt_handshake_timeouts_total 5481
telemt_upstream_connect_attempt_total 7985
telemt_upstream_connect_success_total 7719
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 7985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4014
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_keepalive_timeout_total 966
telemt_me_reconnect_attempts_total 26814
telemt_me_reconnect_success_total 5876
telemt_me_reader_eof_total 6641
telemt_me_idle_close_by_peer_total 6640
telemt_me_route_drop_no_conn_total 215545
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 532952
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1463
telemt_desync_full_logged_total 455
telemt_desync_suppressed_total 1008
telemt_desync_frames_bucket_total{bucket="1_2"} 441
telemt_desync_frames_bucket_total{bucket="3_10"} 586
telemt_desync_frames_bucket_total{bucket="gt_10"} 436
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 6577
telemt_me_refill_failed_total 652
telemt_me_writer_restored_same_endpoint_total 5872
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 701
telemt_user_connections_total{user="hello"} 532905
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 6213947448 (5.79 GB)
telemt_user_octets_to_client{user="hello"} 169878169352 (158.21 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 70
```