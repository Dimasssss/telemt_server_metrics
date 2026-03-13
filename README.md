# Server Metrics 2026-03-13 07:40:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 92517.5 (25h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2546835
telemt_connections_bad_total 36168
telemt_handshake_timeouts_total 26664
telemt_upstream_connect_attempt_total 18012
telemt_upstream_connect_success_total 17912
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 18012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8595
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 1351
telemt_me_reconnect_attempts_total 22197
telemt_me_reconnect_success_total 13324
telemt_me_reader_eof_total 14364
telemt_me_idle_close_by_peer_total 14363
telemt_me_route_drop_no_conn_total 955540
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2334418
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10530
telemt_desync_full_logged_total 2714
telemt_desync_suppressed_total 7816
telemt_desync_frames_bucket_total{bucket="1_2"} 2685
telemt_desync_frames_bucket_total{bucket="3_10"} 3892
telemt_desync_frames_bucket_total{bucket="gt_10"} 3953
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 13788
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 13311
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 2333919
telemt_user_connections_current{user="hello"} 1597
telemt_user_octets_from_client{user="hello"} 33315109320 (31.03 GB)
telemt_user_octets_to_client{user="hello"} 784166302284 (730.31 GB)
telemt_user_unique_ips_current{user="hello"} 438
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 122137.9 (33h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1031145
telemt_connections_bad_total 13051
telemt_handshake_timeouts_total 66144
telemt_upstream_connect_attempt_total 30620
telemt_upstream_connect_success_total 30589
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 30620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14711
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3609
telemt_me_reconnect_attempts_total 23006
telemt_me_reconnect_success_total 22886
telemt_me_reader_eof_total 24390
telemt_me_idle_close_by_peer_total 24390
telemt_me_route_drop_no_conn_total 322628
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 912021
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3989
telemt_desync_full_logged_total 1223
telemt_desync_suppressed_total 2766
telemt_desync_frames_bucket_total{bucket="1_2"} 1515
telemt_desync_frames_bucket_total{bucket="3_10"} 1278
telemt_desync_frames_bucket_total{bucket="gt_10"} 1196
telemt_pool_swap_total 125
telemt_me_writer_removed_unexpected_total 23109
telemt_me_writer_restored_same_endpoint_total 22877
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 913947
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 14066600160 (13.10 GB)
telemt_user_octets_to_client{user="hello"} 343150345199 (319.58 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 122137.8 (33h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2065327
telemt_connections_bad_total 23379
telemt_handshake_timeouts_total 138188
telemt_upstream_connect_attempt_total 28104
telemt_upstream_connect_success_total 28094
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 28104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13261
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1732
telemt_me_reconnect_attempts_total 22954
telemt_me_reconnect_success_total 21678
telemt_me_reader_eof_total 22966
telemt_me_idle_close_by_peer_total 22965
telemt_me_route_drop_no_conn_total 664521
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1637720
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5530
telemt_desync_full_logged_total 1717
telemt_desync_suppressed_total 3813
telemt_desync_frames_bucket_total{bucket="1_2"} 909
telemt_desync_frames_bucket_total{bucket="3_10"} 2011
telemt_desync_frames_bucket_total{bucket="gt_10"} 2610
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 21889
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 21637
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 211
telemt_user_connections_total{user="hello"} 1637198
telemt_user_connections_current{user="hello"} 886
telemt_user_octets_from_client{user="hello"} 27292550096 (25.42 GB)
telemt_user_octets_to_client{user="hello"} 595185955621 (554.31 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 122138.3 (33h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1275850
telemt_connections_bad_total 14140
telemt_handshake_timeouts_total 81661
telemt_upstream_connect_attempt_total 41094
telemt_upstream_connect_success_total 38797
telemt_upstream_connect_fail_total 2160
telemt_upstream_connect_attempts_per_request{bucket="1"} 40820
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14998
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2159
telemt_me_keepalive_timeout_total 11434
telemt_me_reconnect_attempts_total 35806
telemt_me_reconnect_success_total 26868
telemt_me_reader_eof_total 28946
telemt_me_idle_close_by_peer_total 28939
telemt_me_route_drop_no_conn_total 458604
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1090555
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2161
telemt_desync_full_logged_total 701
telemt_desync_suppressed_total 1460
telemt_desync_frames_bucket_total{bucket="1_2"} 592
telemt_desync_frames_bucket_total{bucket="3_10"} 832
telemt_desync_frames_bucket_total{bucket="gt_10"} 737
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 27333
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 26844
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 465
telemt_user_connections_total{user="hello"} 1095298
telemt_user_connections_current{user="hello"} 527
telemt_user_octets_from_client{user="hello"} 16629422193 (15.49 GB)
telemt_user_octets_to_client{user="hello"} 433342976030 (403.58 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 122138.1 (33h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1436432
telemt_connections_bad_total 25560
telemt_handshake_timeouts_total 11970
telemt_upstream_connect_attempt_total 38637
telemt_upstream_connect_success_total 38166
telemt_upstream_connect_fail_total 471
telemt_upstream_connect_attempts_per_request{bucket="1"} 38637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18588
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 471
telemt_me_keepalive_timeout_total 2109
telemt_me_reconnect_attempts_total 45843
telemt_me_reconnect_success_total 32104
telemt_me_reader_eof_total 33701
telemt_me_idle_close_by_peer_total 33701
telemt_me_seq_mismatch_total 44
telemt_me_route_drop_no_conn_total 527911
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1320947
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 48
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4695
telemt_desync_full_logged_total 1673
telemt_desync_suppressed_total 3022
telemt_desync_frames_bucket_total{bucket="1_2"} 1429
telemt_desync_frames_bucket_total{bucket="3_10"} 1513
telemt_desync_frames_bucket_total{bucket="gt_10"} 1753
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 32884
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 32048
telemt_me_writer_restored_fallback_total 56
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 780
telemt_user_connections_total{user="hello"} 1320756
telemt_user_connections_current{user="hello"} 867
telemt_user_octets_from_client{user="hello"} 16691885520 (15.55 GB)
telemt_user_octets_to_client{user="hello"} 452570122888 (421.49 GB)
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 120
```