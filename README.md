# Server Metrics 2026-03-14 08:58:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 183574.5 (50h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5209824
telemt_connections_bad_total 47073
telemt_handshake_timeouts_total 117438
telemt_upstream_connect_attempt_total 38529
telemt_upstream_connect_success_total 38279
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 38529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17381
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_keepalive_timeout_total 7423
telemt_me_reconnect_attempts_total 38050
telemt_me_reconnect_success_total 26837
telemt_me_reader_eof_total 28804
telemt_me_idle_close_by_peer_total 28803
telemt_me_route_drop_no_conn_total 1971017
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4776880
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18269
telemt_desync_full_logged_total 4982
telemt_desync_suppressed_total 13287
telemt_desync_frames_bucket_total{bucket="1_2"} 4524
telemt_desync_frames_bucket_total{bucket="3_10"} 6949
telemt_desync_frames_bucket_total{bucket="gt_10"} 6796
telemt_pool_swap_total 159
telemt_me_writer_removed_unexpected_total 27579
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 26824
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 742
telemt_user_connections_total{user="hello"} 4778329
telemt_user_connections_current{user="hello"} 1899
telemt_user_octets_from_client{user="hello"} 73155479908 (68.13 GB)
telemt_user_octets_to_client{user="hello"} 1528402412661 (1.39 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 505
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 83238.4 (23h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 920274
telemt_connections_bad_total 54186
telemt_handshake_timeouts_total 18208
telemt_upstream_connect_attempt_total 22258
telemt_upstream_connect_success_total 21972
telemt_upstream_connect_fail_total 286
telemt_upstream_connect_attempts_per_request{bucket="1"} 22258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 286
telemt_me_keepalive_timeout_total 2180
telemt_me_reconnect_attempts_total 23013
telemt_me_reconnect_success_total 15798
telemt_me_reader_eof_total 16870
telemt_me_idle_close_by_peer_total 16869
telemt_me_route_drop_no_conn_total 306600
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 746011
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2173
telemt_desync_full_logged_total 681
telemt_desync_suppressed_total 1492
telemt_desync_frames_bucket_total{bucket="1_2"} 494
telemt_desync_frames_bucket_total{bucket="3_10"} 933
telemt_desync_frames_bucket_total{bucket="gt_10"} 746
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 16249
telemt_me_refill_failed_total 219
telemt_me_writer_restored_same_endpoint_total 15790
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 451
telemt_user_connections_total{user="hello"} 747910
telemt_user_connections_current{user="hello"} 591
telemt_user_octets_from_client{user="hello"} 7974673909 (7.43 GB)
telemt_user_octets_to_client{user="hello"} 257987886540 (240.27 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 213195.1 (59h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3718519
telemt_connections_bad_total 44206
telemt_handshake_timeouts_total 245329
telemt_upstream_connect_attempt_total 48131
telemt_upstream_connect_success_total 48110
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 48131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22446
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10794
telemt_me_reconnect_attempts_total 42193
telemt_me_reconnect_success_total 37203
telemt_me_reader_eof_total 39495
telemt_me_idle_close_by_peer_total 39494
telemt_me_route_drop_no_conn_total 1276184
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3104272
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10121
telemt_desync_full_logged_total 3438
telemt_desync_suppressed_total 6683
telemt_desync_frames_bucket_total{bucket="1_2"} 1791
telemt_desync_frames_bucket_total{bucket="3_10"} 3673
telemt_desync_frames_bucket_total{bucket="gt_10"} 4657
telemt_pool_swap_total 200
telemt_me_writer_removed_unexpected_total 37717
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 37162
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 514
telemt_user_connections_total{user="hello"} 3103422
telemt_user_connections_current{user="hello"} 746
telemt_user_octets_from_client{user="hello"} 52557560508 (48.95 GB)
telemt_user_octets_to_client{user="hello"} 1107729874125 (1.01 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 213197.6 (59h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2462772
telemt_connections_bad_total 23357
telemt_handshake_timeouts_total 302029
telemt_upstream_connect_attempt_total 66256
telemt_upstream_connect_success_total 63758
telemt_upstream_connect_fail_total 2361
telemt_upstream_connect_attempts_per_request{bucket="1"} 65982
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2360
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20585
telemt_me_reconnect_attempts_total 56510
telemt_me_reconnect_success_total 46144
telemt_me_reader_eof_total 49440
telemt_me_idle_close_by_peer_total 49433
telemt_me_route_drop_no_conn_total 824993
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1935780
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3970
telemt_desync_full_logged_total 1295
telemt_desync_suppressed_total 2675
telemt_desync_frames_bucket_total{bucket="1_2"} 1099
telemt_desync_frames_bucket_total{bucket="3_10"} 1630
telemt_desync_frames_bucket_total{bucket="gt_10"} 1241
telemt_pool_swap_total 186
telemt_me_writer_removed_unexpected_total 46864
telemt_me_refill_failed_total 315
telemt_me_writer_restored_same_endpoint_total 46120
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 720
telemt_user_connections_total{user="hello"} 1941926
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 29053986171 (27.06 GB)
telemt_user_octets_to_client{user="hello"} 705003206690 (656.59 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 82631.0 (22h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 904474
telemt_connections_bad_total 11901
telemt_handshake_timeouts_total 11270
telemt_upstream_connect_attempt_total 20810
telemt_upstream_connect_success_total 20255
telemt_upstream_connect_fail_total 555
telemt_upstream_connect_attempts_per_request{bucket="1"} 20810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10520
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 555
telemt_me_keepalive_timeout_total 1638
telemt_me_reconnect_attempts_total 66685
telemt_me_reconnect_success_total 16150
telemt_me_reader_eof_total 18128
telemt_me_idle_close_by_peer_total 18127
telemt_me_route_drop_no_conn_total 345247
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 841495
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2195
telemt_desync_full_logged_total 688
telemt_desync_suppressed_total 1507
telemt_desync_frames_bucket_total{bucket="1_2"} 702
telemt_desync_frames_bucket_total{bucket="3_10"} 840
telemt_desync_frames_bucket_total{bucket="gt_10"} 653
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 17874
telemt_me_refill_failed_total 1574
telemt_me_writer_restored_same_endpoint_total 16145
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1724
telemt_user_connections_total{user="hello"} 841384
telemt_user_connections_current{user="hello"} 737
telemt_user_octets_from_client{user="hello"} 15185367280 (14.14 GB)
telemt_user_octets_to_client{user="hello"} 286062808144 (266.42 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 92
```