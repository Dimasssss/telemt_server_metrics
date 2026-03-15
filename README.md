# Server Metrics 2026-03-15 18:20:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 72353.7 (20h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2589609
telemt_connections_bad_total 151603
telemt_handshake_timeouts_total 33920
telemt_upstream_connect_attempt_total 13991
telemt_upstream_connect_success_total 13931
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 13991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 15202
telemt_me_reconnect_success_total 10303
telemt_me_reader_eof_total 11015
telemt_me_idle_close_by_peer_total 11015
telemt_me_route_drop_no_conn_total 898192
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2163222
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8378
telemt_desync_full_logged_total 2296
telemt_desync_suppressed_total 6082
telemt_desync_frames_bucket_total{bucket="1_2"} 2071
telemt_desync_frames_bucket_total{bucket="3_10"} 3191
telemt_desync_frames_bucket_total{bucket="gt_10"} 3116
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 10630
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 10292
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 2162692
telemt_user_connections_current{user="hello"} 2463
telemt_user_octets_from_client{user="hello"} 32657651704 (30.41 GB)
telemt_user_octets_to_client{user="hello"} 825452194764 (768.76 GB)
telemt_user_unique_ips_current{user="hello"} 679
telemt_user_unique_ips_recent_window{user="hello"} 300
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 72354.2 (20h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1002052
telemt_connections_bad_total 57350
telemt_handshake_timeouts_total 64083
telemt_upstream_connect_attempt_total 17940
telemt_upstream_connect_success_total 17843
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 17940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8205
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 15068
telemt_me_reconnect_success_total 13856
telemt_me_reader_eof_total 14663
telemt_me_idle_close_by_peer_total 14663
telemt_me_route_drop_no_conn_total 260165
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 774725
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2233
telemt_desync_full_logged_total 761
telemt_desync_suppressed_total 1472
telemt_desync_frames_bucket_total{bucket="1_2"} 780
telemt_desync_frames_bucket_total{bucket="3_10"} 843
telemt_desync_frames_bucket_total{bucket="gt_10"} 610
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 14074
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13844
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 774953
telemt_user_connections_current{user="hello"} 856
telemt_user_octets_from_client{user="hello"} 11206157647 (10.44 GB)
telemt_user_octets_to_client{user="hello"} 290884208640 (270.91 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 72354.2 (20h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2195241
telemt_connections_bad_total 51201
telemt_handshake_timeouts_total 215524
telemt_upstream_connect_attempt_total 15558
telemt_upstream_connect_success_total 15479
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 15558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7401
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 13091
telemt_me_reconnect_success_total 11821
telemt_me_reader_eof_total 12525
telemt_me_idle_close_by_peer_total 12525
telemt_me_route_drop_no_conn_total 572603
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1377299
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3605
telemt_desync_full_logged_total 1296
telemt_desync_suppressed_total 2309
telemt_desync_frames_bucket_total{bucket="1_2"} 822
telemt_desync_frames_bucket_total{bucket="3_10"} 1405
telemt_desync_frames_bucket_total{bucket="gt_10"} 1378
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12027
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11802
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 1373174
telemt_user_connections_current{user="hello"} 1456
telemt_user_octets_from_client{user="hello"} 25468337268 (23.72 GB)
telemt_user_octets_to_client{user="hello"} 514769984848 (479.42 GB)
telemt_user_unique_ips_current{user="hello"} 428
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 72354.0 (20h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1067015
telemt_connections_bad_total 82090
telemt_handshake_timeouts_total 52374
telemt_upstream_connect_attempt_total 170977
telemt_upstream_connect_success_total 170372
telemt_upstream_connect_fail_total 605
telemt_upstream_connect_attempts_per_request{bucket="1"} 170977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13408
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 605
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 61840
telemt_me_reconnect_success_total 13774
telemt_me_reader_eof_total 15650
telemt_me_idle_close_by_peer_total 15650
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 254221
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 679116
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 44
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1898
telemt_desync_full_logged_total 528
telemt_desync_suppressed_total 1370
telemt_desync_frames_bucket_total{bucket="1_2"} 486
telemt_desync_frames_bucket_total{bucket="3_10"} 731
telemt_desync_frames_bucket_total{bucket="gt_10"} 681
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 15420
telemt_me_refill_failed_total 1504
telemt_me_writer_restored_same_endpoint_total 13738
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1646
telemt_user_connections_total{user="hello"} 831629
telemt_user_connections_current{user="hello"} 960
telemt_user_octets_from_client{user="hello"} 15390060365 (14.33 GB)
telemt_user_octets_to_client{user="hello"} 296766023584 (276.38 GB)
telemt_user_msgs_from_client{user="hello"} 3035962
telemt_user_msgs_to_client{user="hello"} 10927629
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 72354.6 (20h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1081957
telemt_connections_bad_total 12636
telemt_handshake_timeouts_total 23471
telemt_upstream_connect_attempt_total 15878
telemt_upstream_connect_success_total 15793
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 15878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8462
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 15852
telemt_me_reconnect_success_total 12157
telemt_me_reader_eof_total 12969
telemt_me_idle_close_by_peer_total 12969
telemt_me_route_drop_no_conn_total 273929
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 897739
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3147
telemt_desync_full_logged_total 1034
telemt_desync_suppressed_total 2113
telemt_desync_frames_bucket_total{bucket="1_2"} 947
telemt_desync_frames_bucket_total{bucket="3_10"} 1160
telemt_desync_frames_bucket_total{bucket="gt_10"} 1040
telemt_pool_swap_total 61
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 12418
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 12149
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 261
telemt_user_connections_total{user="hello"} 897761
telemt_user_connections_current{user="hello"} 948
telemt_user_octets_from_client{user="hello"} 11057697704 (10.30 GB)
telemt_user_octets_to_client{user="hello"} 314499487748 (292.90 GB)
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 104
```