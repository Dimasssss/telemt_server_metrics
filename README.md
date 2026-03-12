# Server Metrics 2026-03-12 18:40:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 45681.3 (12h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1631899
telemt_connections_bad_total 20494
telemt_handshake_timeouts_total 15080
telemt_upstream_connect_attempt_total 9068
telemt_upstream_connect_success_total 9017
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 9068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4274
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 568
telemt_me_reconnect_attempts_total 15545
telemt_me_reconnect_success_total 6700
telemt_me_reader_eof_total 7255
telemt_me_idle_close_by_peer_total 7254
telemt_me_route_drop_no_conn_total 638509
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1528526
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7817
telemt_desync_full_logged_total 1983
telemt_desync_suppressed_total 5834
telemt_desync_frames_bucket_total{bucket="1_2"} 2027
telemt_desync_frames_bucket_total{bucket="3_10"} 2836
telemt_desync_frames_bucket_total{bucket="gt_10"} 2954
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 7070
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 6687
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 1528013
telemt_user_connections_current{user="hello"} 1437
telemt_user_octets_from_client{user="hello"} 23693135044 (22.07 GB)
telemt_user_octets_to_client{user="hello"} 513759769188 (478.48 GB)
telemt_user_unique_ips_current{user="hello"} 386
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 75301.9 (20h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 701474
telemt_connections_bad_total 9108
telemt_handshake_timeouts_total 29442
telemt_upstream_connect_attempt_total 19285
telemt_upstream_connect_success_total 19256
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 19285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8979
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3365
telemt_me_reconnect_attempts_total 13918
telemt_me_reconnect_success_total 13833
telemt_me_reader_eof_total 14706
telemt_me_idle_close_by_peer_total 14706
telemt_me_route_drop_no_conn_total 223837
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 631724
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2769
telemt_desync_full_logged_total 849
telemt_desync_suppressed_total 1920
telemt_desync_frames_bucket_total{bucket="1_2"} 1102
telemt_desync_frames_bucket_total{bucket="3_10"} 907
telemt_desync_frames_bucket_total{bucket="gt_10"} 760
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 13980
telemt_me_writer_restored_same_endpoint_total 13824
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 633604
telemt_user_connections_current{user="hello"} 510
telemt_user_octets_from_client{user="hello"} 9688658240 (9.02 GB)
telemt_user_octets_to_client{user="hello"} 238501587415 (222.12 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 75301.8 (20h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1452928
telemt_connections_bad_total 6996
telemt_handshake_timeouts_total 100451
telemt_upstream_connect_attempt_total 17923
telemt_upstream_connect_success_total 17918
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 17923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8212
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1183
telemt_me_reconnect_attempts_total 15023
telemt_me_reconnect_success_total 13779
telemt_me_reader_eof_total 14527
telemt_me_idle_close_by_peer_total 14526
telemt_me_route_drop_no_conn_total 478903
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1110717
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4680
telemt_desync_full_logged_total 1443
telemt_desync_suppressed_total 3237
telemt_desync_frames_bucket_total{bucket="1_2"} 729
telemt_desync_frames_bucket_total{bucket="3_10"} 1696
telemt_desync_frames_bucket_total{bucket="gt_10"} 2255
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 13902
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 13738
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 1110580
telemt_user_connections_current{user="hello"} 806
telemt_user_octets_from_client{user="hello"} 16705617560 (15.56 GB)
telemt_user_octets_to_client{user="hello"} 404623776193 (376.84 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 75302.5 (20h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 885944
telemt_connections_bad_total 12509
telemt_handshake_timeouts_total 65588
telemt_upstream_connect_attempt_total 19509
telemt_upstream_connect_success_total 19433
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 19509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 1626
telemt_me_reconnect_attempts_total 23385
telemt_me_reconnect_success_total 15661
telemt_me_reader_eof_total 16727
telemt_me_idle_close_by_peer_total 16727
telemt_me_route_drop_no_conn_total 312551
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 765776
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1735
telemt_desync_full_logged_total 581
telemt_desync_suppressed_total 1154
telemt_desync_frames_bucket_total{bucket="1_2"} 487
telemt_desync_frames_bucket_total{bucket="3_10"} 674
telemt_desync_frames_bucket_total{bucket="gt_10"} 574
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 16028
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 15640
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 367
telemt_user_connections_total{user="hello"} 765138
telemt_user_connections_current{user="hello"} 497
telemt_user_octets_from_client{user="hello"} 9329346436 (8.69 GB)
telemt_user_octets_to_client{user="hello"} 312811417236 (291.33 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 75302.1 (20h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 992767
telemt_connections_bad_total 11476
telemt_handshake_timeouts_total 8208
telemt_upstream_connect_attempt_total 23645
telemt_upstream_connect_success_total 23364
telemt_upstream_connect_fail_total 281
telemt_upstream_connect_attempts_per_request{bucket="1"} 23645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11271
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 281
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 30609
telemt_me_reconnect_success_total 19575
telemt_me_reader_eof_total 20576
telemt_me_idle_close_by_peer_total 20576
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 368887
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 911210
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3474
telemt_desync_full_logged_total 1204
telemt_desync_suppressed_total 2270
telemt_desync_frames_bucket_total{bucket="1_2"} 974
telemt_desync_frames_bucket_total{bucket="3_10"} 1169
telemt_desync_frames_bucket_total{bucket="gt_10"} 1331
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 20141
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 19531
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 566
telemt_user_connections_total{user="hello"} 911087
telemt_user_connections_current{user="hello"} 673
telemt_user_octets_from_client{user="hello"} 11294197652 (10.52 GB)
telemt_user_octets_to_client{user="hello"} 304479773848 (283.57 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 99
```