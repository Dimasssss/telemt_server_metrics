# Server Metrics 2026-03-14 07:15:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 177437.2 (49h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5003096
telemt_connections_bad_total 40206
telemt_handshake_timeouts_total 113597
telemt_upstream_connect_attempt_total 37192
telemt_upstream_connect_success_total 36949
telemt_upstream_connect_fail_total 243
telemt_upstream_connect_attempts_per_request{bucket="1"} 37192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16732
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 243
telemt_me_keepalive_timeout_total 7343
telemt_me_reconnect_attempts_total 35926
telemt_me_reconnect_success_total 25775
telemt_me_reader_eof_total 27657
telemt_me_idle_close_by_peer_total 27656
telemt_me_route_drop_no_conn_total 1893655
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4589802
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17500
telemt_desync_full_logged_total 4759
telemt_desync_suppressed_total 12741
telemt_desync_frames_bucket_total{bucket="1_2"} 4370
telemt_desync_frames_bucket_total{bucket="3_10"} 6657
telemt_desync_frames_bucket_total{bucket="gt_10"} 6473
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 26461
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 25762
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 686
telemt_user_connections_total{user="hello"} 4591291
telemt_user_connections_current{user="hello"} 1515
telemt_user_octets_from_client{user="hello"} 67331525844 (62.71 GB)
telemt_user_octets_to_client{user="hello"} 1453188932069 (1.32 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 424
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 77101.2 (21h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 840547
telemt_connections_bad_total 53817
telemt_handshake_timeouts_total 15354
telemt_upstream_connect_attempt_total 20806
telemt_upstream_connect_success_total 20534
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 20806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9010
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 234
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_keepalive_timeout_total 2145
telemt_me_reconnect_attempts_total 18137
telemt_me_reconnect_success_total 14671
telemt_me_reader_eof_total 15593
telemt_me_idle_close_by_peer_total 15592
telemt_me_route_drop_no_conn_total 276244
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 671595
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1964
telemt_desync_full_logged_total 602
telemt_desync_suppressed_total 1362
telemt_desync_frames_bucket_total{bucket="1_2"} 413
telemt_desync_frames_bucket_total{bucket="3_10"} 872
telemt_desync_frames_bucket_total{bucket="gt_10"} 679
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 14987
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 14663
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 316
telemt_user_connections_total{user="hello"} 673509
telemt_user_connections_current{user="hello"} 524
telemt_user_octets_from_client{user="hello"} 7044958621 (6.56 GB)
telemt_user_octets_to_client{user="hello"} 229639107008 (213.87 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 207057.8 (57h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3588210
telemt_connections_bad_total 42311
telemt_handshake_timeouts_total 235612
telemt_upstream_connect_attempt_total 46711
telemt_upstream_connect_success_total 46690
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 46711
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21842
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 242
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10706
telemt_me_reconnect_attempts_total 41060
telemt_me_reconnect_success_total 36084
telemt_me_reader_eof_total 38329
telemt_me_idle_close_by_peer_total 38328
telemt_me_route_drop_no_conn_total 1227034
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2991986
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9845
telemt_desync_full_logged_total 3307
telemt_desync_suppressed_total 6538
telemt_desync_frames_bucket_total{bucket="1_2"} 1721
telemt_desync_frames_bucket_total{bucket="3_10"} 3559
telemt_desync_frames_bucket_total{bucket="gt_10"} 4565
telemt_pool_swap_total 196
telemt_me_writer_removed_unexpected_total 36584
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 36043
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 500
telemt_user_connections_total{user="hello"} 2991139
telemt_user_connections_current{user="hello"} 817
telemt_user_octets_from_client{user="hello"} 50082771888 (46.64 GB)
telemt_user_octets_to_client{user="hello"} 1068388992377 (995.01 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 207060.4 (57h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2389305
telemt_connections_bad_total 23302
telemt_handshake_timeouts_total 285887
telemt_upstream_connect_attempt_total 64464
telemt_upstream_connect_success_total 61975
telemt_upstream_connect_fail_total 2352
telemt_upstream_connect_attempts_per_request{bucket="1"} 64190
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24835
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2351
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20518
telemt_me_reconnect_attempts_total 53709
telemt_me_reconnect_success_total 44663
telemt_me_reader_eof_total 47860
telemt_me_idle_close_by_peer_total 47853
telemt_me_route_drop_no_conn_total 804065
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1882426
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3926
telemt_desync_full_logged_total 1276
telemt_desync_suppressed_total 2650
telemt_desync_frames_bucket_total{bucket="1_2"} 1077
telemt_desync_frames_bucket_total{bucket="3_10"} 1618
telemt_desync_frames_bucket_total{bucket="gt_10"} 1231
telemt_pool_swap_total 183
telemt_me_writer_removed_unexpected_total 45329
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 44639
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 666
telemt_user_connections_total{user="hello"} 1888503
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 28412814571 (26.46 GB)
telemt_user_octets_to_client{user="hello"} 693127988654 (645.53 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 76494.2 (21h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 812453
telemt_connections_bad_total 8268
telemt_handshake_timeouts_total 9547
telemt_upstream_connect_attempt_total 19542
telemt_upstream_connect_success_total 19016
telemt_upstream_connect_fail_total 526
telemt_upstream_connect_attempts_per_request{bucket="1"} 19542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9892
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 526
telemt_me_keepalive_timeout_total 1586
telemt_me_reconnect_attempts_total 60529
telemt_me_reconnect_success_total 15221
telemt_me_reader_eof_total 17003
telemt_me_idle_close_by_peer_total 17002
telemt_me_route_drop_no_conn_total 313258
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 759080
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1854
telemt_desync_full_logged_total 591
telemt_desync_suppressed_total 1263
telemt_desync_frames_bucket_total{bucket="1_2"} 554
telemt_desync_frames_bucket_total{bucket="3_10"} 714
telemt_desync_frames_bucket_total{bucket="gt_10"} 586
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 16765
telemt_me_refill_failed_total 1411
telemt_me_writer_restored_same_endpoint_total 15216
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1544
telemt_user_connections_total{user="hello"} 758940
telemt_user_connections_current{user="hello"} 613
telemt_user_octets_from_client{user="hello"} 13525169488 (12.60 GB)
telemt_user_octets_to_client{user="hello"} 255961953348 (238.38 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 78
```