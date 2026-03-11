# Server Metrics 2026-03-11 07:07:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 60014.3 (16h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1196508
telemt_connections_bad_total 13289
telemt_handshake_timeouts_total 38817
telemt_upstream_connect_attempt_total 12593
telemt_upstream_connect_success_total 12584
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 12593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6193
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 714
telemt_me_reconnect_attempts_total 21230
telemt_me_reconnect_success_total 9547
telemt_me_reader_eof_total 10376
telemt_me_idle_close_by_peer_total 10376
telemt_me_route_drop_no_conn_total 440036
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1078977
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5239
telemt_desync_full_logged_total 1468
telemt_desync_suppressed_total 3771
telemt_desync_frames_bucket_total{bucket="1_2"} 1396
telemt_desync_frames_bucket_total{bucket="3_10"} 1963
telemt_desync_frames_bucket_total{bucket="gt_10"} 1880
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10005
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9541
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 458
telemt_user_connections_total{user="hello"} 1078640
telemt_user_connections_current{user="hello"} 1418
telemt_user_octets_from_client{user="hello"} 14257432128 (13.28 GB)
telemt_user_octets_to_client{user="hello"} 319165954552 (297.25 GB)
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 60071.1 (16h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 462325
telemt_connections_bad_total 5831
telemt_handshake_timeouts_total 22348
telemt_upstream_connect_attempt_total 21364
telemt_upstream_connect_success_total 18450
telemt_upstream_connect_fail_total 2914
telemt_upstream_connect_attempts_per_request{bucket="1"} 21364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7905
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2914
telemt_me_keepalive_timeout_total 2039
telemt_me_reconnect_attempts_total 13323
telemt_me_reconnect_success_total 12498
telemt_me_reader_eof_total 13218
telemt_me_idle_close_by_peer_total 13216
telemt_me_route_drop_no_conn_total 206567
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 395735
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1992
telemt_desync_full_logged_total 610
telemt_desync_suppressed_total 1382
telemt_desync_frames_bucket_total{bucket="1_2"} 648
telemt_desync_frames_bucket_total{bucket="3_10"} 713
telemt_desync_frames_bucket_total{bucket="gt_10"} 631
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 12644
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 12476
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 398003
telemt_user_connections_current{user="hello"} 476
telemt_user_octets_from_client{user="hello"} 3928154450 (3.66 GB)
telemt_user_octets_to_client{user="hello"} 102461235284 (95.42 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 60070.9 (16h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 784368
telemt_connections_bad_total 6822
telemt_handshake_timeouts_total 42384
telemt_upstream_connect_attempt_total 16202
telemt_upstream_connect_success_total 15996
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 16202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7199
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 724
telemt_me_reconnect_attempts_total 22992
telemt_me_reconnect_success_total 11918
telemt_me_reader_eof_total 12814
telemt_me_idle_close_by_peer_total 12814
telemt_me_route_drop_no_conn_total 265689
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 701715
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2025
telemt_desync_full_logged_total 586
telemt_desync_suppressed_total 1439
telemt_desync_frames_bucket_total{bucket="1_2"} 469
telemt_desync_frames_bucket_total{bucket="3_10"} 735
telemt_desync_frames_bucket_total{bucket="gt_10"} 821
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 12413
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 11907
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 495
telemt_user_connections_total{user="hello"} 702520
telemt_user_connections_current{user="hello"} 709
telemt_user_octets_from_client{user="hello"} 8250173949 (7.68 GB)
telemt_user_octets_to_client{user="hello"} 206812595517 (192.61 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 60071.3 (16h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 600407
telemt_connections_bad_total 56287
telemt_handshake_timeouts_total 60035
telemt_upstream_connect_attempt_total 16989
telemt_upstream_connect_success_total 16989
telemt_upstream_connect_attempts_per_request{bucket="1"} 16989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7474
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 658
telemt_me_reconnect_attempts_total 15035
telemt_me_reconnect_success_total 13987
telemt_me_reader_eof_total 14852
telemt_me_idle_close_by_peer_total 14852
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 183204
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 463881
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1011
telemt_desync_full_logged_total 408
telemt_desync_suppressed_total 603
telemt_desync_frames_bucket_total{bucket="1_2"} 356
telemt_desync_frames_bucket_total{bucket="3_10"} 374
telemt_desync_frames_bucket_total{bucket="gt_10"} 281
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 14149
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 13965
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 463310
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 5561475100 (5.18 GB)
telemt_user_octets_to_client{user="hello"} 127044061056 (118.32 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 60071.1 (16h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 622407
telemt_connections_bad_total 5966
telemt_handshake_timeouts_total 4512
telemt_upstream_connect_attempt_total 16881
telemt_upstream_connect_success_total 16811
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 16881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8041
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 687
telemt_me_reconnect_attempts_total 17480
telemt_me_reconnect_success_total 13694
telemt_me_reader_eof_total 14471
telemt_me_idle_close_by_peer_total 14471
telemt_me_route_drop_no_conn_total 207172
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 567337
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2656
telemt_desync_full_logged_total 1014
telemt_desync_suppressed_total 1642
telemt_desync_frames_bucket_total{bucket="1_2"} 946
telemt_desync_frames_bucket_total{bucket="3_10"} 1127
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 13989
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 13694
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 567061
telemt_user_connections_current{user="hello"} 670
telemt_user_octets_from_client{user="hello"} 9750722103 (9.08 GB)
telemt_user_octets_to_client{user="hello"} 208498834578 (194.18 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 95
```